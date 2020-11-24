------------------------README-------------------------

A. Generate a public-private key pair with RSA 
1. Run rsa.py in decryption folder
2. Enter 2048 as the number of bits 

publickey.pen and privatekey.pem files will get generated

-------------------------------------------------------

B. To encrypt a message
1. Type the message in plaintext.txt
2. Run encryption.py in encryption folder
3. Enter "plaintext.txt" as the path of file containing the message

cipher.txt with the hash value and encrypted text will be generated
iv.txt with the initialization vector will get generated
enc_key.txt with the encrypted random key for 3-DES will be generated where the random key is encrypted using RSA algorithm

-------------------------------------------------------

C. To decrypt the message
1. Run decryption.txt

The message will be decrypted