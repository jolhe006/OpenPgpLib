# OpenPgpLib

### Available on NuGet

Open PGP Lib for C# .NET based on [Bouncy Castle](http://www.bouncycastle.org/index.html)

> Keys generated on [PGP Key Generator](https://pgpkeygen.com/)

# To encrypt a file

```cs
   OpenPgp.EncryptFile ("YOUR INPUT FILE NAME", "OUTPUT ENCRYPTED FILE NAME", "YOUR PUBLIC KEY FILE NAME", false, false);
```

# To decrypt a file

```cs
OpenPgp.DecryptFile ("YOUR ENCRYPTED INPUT FILE NAME", "OUTPUT DECRYPTED FILE NAME", "YOUR PRIVATE KEY FILE NAME", "PRIVATE KEY PASSPHRASE");
```
