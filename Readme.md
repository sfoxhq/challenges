## SFOX Code Challenges

## Background
Hello and welcome to the SFOX code challenges. We look forward to talking to you more about your experence throughout this interview process.

These challenges are designed to test your ability to solve problems. We realize your time is valuable so please don't spend more then 2 hours on these projects. Try to have fun with them, and reach out if you have any questions.

## Getting started

As you may be able to tell, the challenges in this repo are all encrypted. We are a company that operates in the cryptocurrency space and although we don't expect all candidates to have __Alan Turing__ level math skills, we do expect all engineers on the team to have a basic understanding of cryptography.

When we wrote up the challenges in this repo we encrypted them with a 24 word mnemonic sentence built using the methodology outlined in [bip39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki).

The only problem is that we copied the phrase down wrong. We do, however, know a few things about the phrase that we copied:

- We used the standard bip39 english dictionary
- The words were copied in the correct order
- At least the first two letters of each word is correct
- The last word was copied correctly
- Assignments were encrypted using OpenSSL AES-256-CBC
- The initialization vector was `UWdLUx9/vYBJoVplMViRTA==` (encoded in base64)
- The mnemonic phrase is sha256 hashed to get the key used to encrypt

In order to complete the coding task you were assigned, you will need to write a script that recovers this phrase first. Then you will need to use the recovered phrase to decrypt the coding challenge.

Happy hacking!

## Incorrectly copied mnemonic
```
canvas taxi pudding rent exchange remain erosion august engage family bus swamp gown later shoe chaos erode where spring fever mother half enrich blast
```

## Acceptable languages
- JavaScript
- C++
- Golang

