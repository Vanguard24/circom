# Circom

To successfully complete the Final Challenge, you need to follow these steps:

1. **Write a correct circuit.circom implementation**: You should create a circuit in circom that represents the functionality you want to prove. Make sure your circuit accurately represents the constraints and computations required by your problem.

2. **Compile the circuit to generate circuit intermediaries**: Once you have written your circuit, use the circom compiler to generate the necessary files for generating proofs. This typically involves running the circom compiler on your circuit file to produce the constraint system file and other necessary intermediary files.

3. **Generate a proof using inputs A=0 B=1**: After compiling the circuit, you need to generate a proof using specific inputs. In your case, you should provide inputs A=0 and B=1 and generate a proof for these inputs using the compiled circuit.

4. **Deploy a solidity verifier to Sepolia or Mumbai Testnet**: Write a Solidity contract that can verify proofs generated from your circuit. You can use a development environment like Remix or Truffle to write and deploy your contract to the Sepolia or Mumbai Testnet.

5. **Call the verifyProof() method on the verifier contract and assert output is true**: Once your verifier contract is deployed, call the verifyProof() method with the generated proof and inputs. Ensure that the output is true, indicating that the proof is valid for the given inputs.


