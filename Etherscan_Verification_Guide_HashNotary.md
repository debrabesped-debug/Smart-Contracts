# Etherscan Verification Guide for HashNotary Contract

## Introduction
This guide provides detailed step-by-step instructions for verifying the HashNotary contract on Etherscan.

### Contract Address
The HashNotary contract can be found at the following address:

```
0x539ea9Eac4B38C371d9c82b4239b78135C5D5d40
```

### Prerequisites
Before proceeding, ensure that you have the following:
1. The **ABI** (Application Binary Interface) of the contract.
2. The **Bytecode** of the contract.
3. The complete **source code** of the contract.
4. The **compiler version** used for deploying the contract.
5. The **constructor arguments** (if any).

### Step-by-Step Verification Process

#### Step 1: Navigate to Etherscan
1. Go to [Etherscan](https://etherscan.io)
2. Enter the contract address in the search bar: `0x539ea9Eac4B38C371d9c82b4239b78135C5D5d40`

#### Step 2: Open Contract Page
1. Once you find the contract, click on the `Contract` tab.
2. Click on the `Verify and Publish` button to start the verification process.

#### Step 3: Enter Contract Details
1. In the verification form, fill in the following details:
   - **Contract Address**: `0x539ea9Eac4B38C371d9c82b4239b78135C5D5d40`
   - **Compiler Version**: Select the compiler version used.
   - **Optimization**: Indicate whether optimization was used during compiling.

#### Step 4: Enter Contract Source Code
1. Copy the complete source code of the HashNotary contract and paste it into the provided field.

#### Step 5: Enter ABI and Bytecode
1. In the verification form:
   - Paste the **ABI** of the contract.
   - Paste the **Bytecode** of the contract (without the `0x` prefix).

#### Step 6: Add Constructor Arguments (if needed)
1. If the contract has constructor arguments, encode them in the format required by Etherscan and paste them in the designated field.

#### Step 7: Submit Verification
1. Review all entered information for accuracy.
2. Click the `Verify` button to submit your verification request.

### ABI, Bytecode, and Function Selectors

#### ABI
```json
[YOUR_ABI_HERE]
```

#### Bytecode
```
0x[YOUR_BYTECODE_HERE]
```

#### Function Selectors
- Each function's selector can be computed as the first 4 bytes of the Keccak-256 hash of the function signature. Example:
   - `functionName(argType1,argType2)` → `0x` + first 4 bytes of hash
   - List out the function selectors for your contract here.

### Conclusion
Once your contract is verified, it will be marked as such on Etherscan, allowing others to interact with it and see its code.

### Further Assistance
For more assistance, refer to the [Etherscan Documentation](https://docs.etherscan.io) or contact the support team for help.