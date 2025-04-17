## Solana-wallet-generator
Use it for generating one or more solana wallets using the "solana-sdk" crate.

### Requirements:
- C compiler (example: GCC)
- Rust, Cargo

### How to run:
- Install the repository via git or just download the zip file.
```bash
git clone https://github.com/capybara0-0/solana-wallet-generator.git
```
- Navigate to the repo directory and run `cargo build` to compile the code then run `cargo run`.
- You will get a screen that looks something like this,
```bash
  Finished `dev` profile [unoptimized + debuginfo] target(s) in 1.24s
     Running `target/debug/Solana-wallet-generator`
Enter the number of keypairs to generate: 

```

### Example output
```bash
Enter the number of keypairs to generate: 
5
Keypair 1: Public Key = DD6p5PN8RQsPYkGhiqk7eHL1Fr3wLuDKVJ3p35abLCgk
Keypair 1: Secret Key = [17, 46, 244, 131, 162, 201, 82, 11, 18, 199, 157, 176, 71, 14, 187, 243, 180, 148, 112, 221, 232, 56, 73, 50, 201, 77, 242, 7, 9, 119, 37, 200, 181, 101, 200, 185, 70, 6, 183, 76, 38, 166, 89, 221, 89, 222, 69, 137, 40, 218, 195, 110, 153, 82, 155, 222, 49, 249, 235, 153, 226, 203, 229, 69]
Keypair 2: Public Key = 9y8aQYD93kLtGqjrATE1ejewrKRfyAdWEabDATnZaW8i
Keypair 2: Secret Key = [239, 53, 231, 92, 22, 198, 238, 41, 191, 185, 162, 198, 24, 188, 28, 31, 139, 56, 84, 189, 193, 152, 234, 135, 121, 177, 109, 175, 61, 107, 173, 70, 133, 62, 150, 62, 61, 127, 148, 1, 37, 18, 238, 65, 196, 49, 213, 47, 90, 39, 194, 18, 222, 143, 80, 179, 139, 102, 102, 191, 9, 178, 42, 27]
Keypair 3: Public Key = Bs1ZLhkTA68Bqr7WVrUtsGTcpc4WVJheAz9ff7MMivwe
Keypair 3: Secret Key = [151, 20, 104, 118, 188, 44, 194, 186, 186, 81, 109, 218, 72, 100, 83, 128, 140, 138, 106, 213, 8, 243, 21, 93, 246, 31, 117, 23, 194, 78, 144, 124, 161, 100, 138, 72, 251, 250, 124, 3, 45, 36, 97, 220, 5, 103, 250, 239, 119, 58, 166, 107, 206, 238, 125, 8, 142, 60, 229, 228, 161, 217, 241, 125]
Keypair 4: Public Key = F9oYYUboGwv6Kn2zuuW7e3ptkjEEoPgYWyTE6izqHKbv
Keypair 4: Secret Key = [149, 207, 109, 62, 126, 16, 103, 166, 170, 159, 112, 224, 41, 8, 184, 21, 245, 190, 252, 137, 199, 2, 36, 70, 131, 0, 62, 194, 247, 67, 249, 76, 210, 68, 228, 6, 201, 123, 85, 150, 83, 181, 158, 240, 149, 136, 115, 209, 74, 24, 140, 167, 1, 19, 114, 183, 201, 20, 191, 249, 142, 27, 56, 81]
Keypair 5: Public Key = 7XHKKwqbExStqSZZ3YpaXez4xH9TU1N54uqA8c4gHm5u
Keypair 5: Secret Key = [107, 243, 42, 140, 167, 247, 199, 219, 166, 120, 94, 187, 250, 211, 20, 87, 112, 108, 92, 43, 104, 218, 18, 205, 73, 81, 165, 126, 32, 10, 134, 64, 96, 231, 254, 142, 163, 104, 170, 23, 106, 47, 224, 74, 236, 155, 100, 133, 145, 195, 219, 197, 115, 68, 65, 134, 165, 135, 157, 107, 40, 38, 249, 92]
```