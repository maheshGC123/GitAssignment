# GitAssignment Code signing Basics
Code signing is a digital signature added to software and applications that verifies that the included code has not been tampered with after it was signed.
A developer adds a digital signature to code or content using a unique private key from a code signing certificate
When a user downloads or encounters signed code, the user’s system software or application uses a public key to decrypt the signature
The system looks for a “root” certificate with an identity that it trusts or recognizes to authenticate the signature
The system then compares the hash used to sign the application against the hash on the downloaded application
