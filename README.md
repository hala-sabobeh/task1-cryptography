# Applied Cryptography- Cryptanalysis of the A5/1 Stream Cipher

##  Project Overview
Alice and Bob are communicating over a GSM network, which secures transmissions using the **A5/1 stream cipher**. As an attacker, we intercepted:
- A portion of the plaintext message (`known_plaintext.txt`)  
- The full encrypted message (`ciphertext.bin`)  
- Initial states of two LFSRs (X and Z) from `initial_states.txt`  

The challenge is to perform a **cryptanalytic attack** to:
1. Recover the **unknown 22-bit initial state of LFSR Y**.  
2. Use the recovered state to generate the keystream.  
3. Decrypt the entire ciphertext to recover the full plaintext message



