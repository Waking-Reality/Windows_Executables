1. Generating Your Keys
Before you can encrypt or sign files, you need a matching pair of cryptographic keys.
Generate Private Key: Click this button and choose a secure location to save your `.pem` file. Never share this key with anyone. It acts as your personal digital ID and master password.
Generate Public Key: Click this button, select the Private Key you just created, and save the resulting Public Key `.pem` file. This is the key you will share with the world so others can send you encrypted files or verify your signatures.
2. Encrypting and Decrypting Files
This tool uses a hybrid encryption method, allowing you to securely encrypt files of any size (documents, videos, archives).
To Encrypt a File (Sending to someone else):
Click Encrypt a File (using Public Key).
Select the recipient's Public Key.
Select the file you want to encrypt.
Save the resulting encrypted package as a `.zip` file.
> **Important Note for Your Recipient:** When you send the encrypted `.zip` file, inform the recipient that this is a custom cryptographic package, not a standard archive. They should not attempt to extract it using standard Windows tools or WinRAR. They must process it through the **Decrypt a File** button in this specific utility to unlock it.
To Decrypt a File (Receiving from someone else):
Click Decrypt a File (using Private Key).
Select your Private Key.
Select the encrypted `.zip` package you received.
Choose a name and location to save the newly unlocked, original file.
3. Signing and Verifying Files
Digital signatures act as a tamper-evident seal. They do not hide the contents of a file; instead, they mathematically prove that the file was authorized by you and hasn't been altered.
To Sign a File (Proving it's yours):
Click Sign a File (using Private Key).
Select your Private Key.
Select the file you want to sign (e.g., a PDF contract or a software executable).
Save the resulting `.sig` file. You will send both the original file and this `.sig` file to your recipient.
To Verify a Signature (Checking someone else's file):
Click Verify Signature (using Public Key).
Select the sender's Public Key.
Select the `.sig` signature file they provided.
Select the original file they sent.
The tool will cross-reference the hash and the key, alerting you with a "Verified OK" message if the file is authentic, or a warning if it has been tampered with.
