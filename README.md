# java-cli-mill-crypto-gzip-compress-rsa-encrypted-bcrypt-encoded

## Description
Encrypt and decrypt password with rsa
encoded with bcrypt.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- java
- mill
  - rsa
  - bcrypt

## Docker stack
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
