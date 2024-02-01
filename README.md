# My GPG Public Key

## Introduction

This repository contains the official GPG public key released by Haoda Fu. You can use this key to securely send encrypted messages or files to me, or to verify digital signatures on documents or emails that I have signed.

## Key Information

```
Key Owner: Haoda Fu
Email: mylastnamefirstname@gmail.com
Key ID: 8C88CE5DC72E96CED5581FC587A7AC396148B732
Fingerprint: 8C88 CE5D C72E 96CE D558  1FC5 87A7 AC39 6148 B732
```

## Using My Public Key
If you wish to send me an encrypted message or file, you can encrypt it using my public key. Here’s how you can do it:

- Import my public key into your GPG keyring:

```
gpg --import [path-to-this-file]
```

Replace `[path-to-this-file]` with the path to the file containing my public key.

- Encrypt your message or file using my public key:
```
gpg --encrypt --recipient 'fuhaoda@gmail.com' [your-file]
```

Replace `[your-file]` with the path to the file you want to encrypt.

- Send the encrypted file to me via your preferred secure method.

## For Verifying Digital Signatures

To verify a digital signature I have made:

- Import my public key into your GPG keyring (if you haven’t already):
```
gpg --import [path-to-this-file]
```

- Use GPG to verify the signature:
```
gpg --verify [signed-file]
```

## Let's build the Web of Trust! Guide on importing, signing, and sharing my GPG public key

### Importing the Public Key from `keys.openpgp.org`
Step 1: Import the Public Key
- Open the terminal or command prompt.
- Execute the following command to import the public key:

```
gpg --keyserver hkps://keys.openpgp.org --recv-keys 8C88CE5DC72E96CED5581FC587A7AC396148B732
```
This command downloads and imports the public key from `keys.openpgp.org` (Or you can go to the website and download it).

Step 2: Verify the Public Key
- Before signing, check the details of the public key to make sure its finger print is the same as listed in this website:
```
$gpg --fingerprint 8C88CE5DC72E96CED5581FC587A7AC396148B732
pub   rsa3072 2024-01-31 [SC]
      8C88 CE5D C72E 96CE D558  1FC5 87A7 AC39 6148 B732
```

### Signing the Public Key
Step 3: Sign the Public Key
- Use the following command to sign the public key:
```
gpg --sign-key 8C88CE5DC72E96CED5581FC587A7AC396148B732
```
- Follow the prompts to complete the signing process.

Step 4: Upload the Signed Key
- After signing, upload the updated public key back to the keyserver:
```
gpg --keyserver hkps://keys.openpgp.org --send-keys 8C88CE5DC72E96CED5581FC587A7AC396148B732
```


## My Public Key (or you can download the same key from this repo `publickey.asc`)
Due to the signatures, my public key that you downloaded from keys.openpgp.org may not look exactly the same as below.
But after you import, all of them should have the same fingerprint as show in this website. All of them can be used to verify my signature. 

-----BEGIN PGP PUBLIC KEY BLOCK-----

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
Pp+sfwYMZ+0=
=6wPv

-----END PGP PUBLIC KEY BLOCK-----
