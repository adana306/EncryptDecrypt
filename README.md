# EncryptDecrypt

Simple HTML page for encrypting and decrypting a file with a password.

## Warning

- For security reasons, this page works only with the HTTPS protocol. 
- This page don't work with the old versions of MS Edge because crypto functions are not correct in the old MS Edge.
The page works with the new MS Edge based on Chromium.


## Encrypting a file

- Select a file with the encrypt button.
- Gives a password.
- Save the encrypted file.

## Decrypting a file

- Select a file with the decrypt button or type the file url (the url must uses the https protocol).
- Gives the password used for encryption.
- Save the decrypted file. JPEG, PNG, PDF and HTML files are directly opened in the browser.

## lauch EncryptDecrypt and directly start decrypting a file

add "?fil=" followed by the file url base 64 encoded to the EncryptDecrypt url. The url must uses the https protocol.

Sample : [https://wwwouaiebe.github.io/EncryptDecrypt/?fil=aHR0cHM6Ly93d3dvdWFpZWJlLmdpdGh1Yi5pby9FbmNyeXB0RGVjcnlwdC9zYW1wbGUuZW5j](https://wwwouaiebe.github.io/EncryptDecrypt/?fil=aHR0cHM6Ly93d3dvdWFpZWJlLmdpdGh1Yi5pby9FbmNyeXB0RGVjcnlwdC9zYW1wbGUuZW5j)

The password is (Mush1544room)

## What if I forgott the password

No solution... put the file to the bin.

## Demo

Go to the [demo - en ](https://wwwouaiebe.github.io/EncryptDecrypt/)

## How to install

Simply download the project and copy the dist/index.html file to your computer or server.
No others files needed. CSS and Javascript are included in the index.html file.
