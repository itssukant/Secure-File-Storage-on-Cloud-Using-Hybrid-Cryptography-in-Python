# Secure-File-Storage-on-Cloud-Using-Hybrid-Cryptography-in-Python

The information over internet is becoming a critical issue due to security problems. We have proposed a system for securing the important data from a file. Cryptography algorithms provides an effective way for protecting sensitive information. It is a method for storing and transmitting data in a form that is only readable by intended users. When the file is being added on the server, the file gets converted into byte array. The byte array will further divide into three different parts and each part is encrypted into respective techniques namely, AES, DES and RC2. Advanced Encryption Standard (AES) is more popular and widely used symmetric encryption algorithm. With the increasing computing power, it was considered vulnerable against exhaustive key search attack. The Data Encryption Standard (DES) is a symmetric-key block cipher. DES is an implementation of a Feistel Cipher. It uses 16 round Feistel structure. The block size of DES is 64-bit. Though, key length is 64-bit, DES has an effective key length of 56 bits, since 8 of the 64 bits of the key are not used by the encryption algorithm. RC2 (Rivest Cipher) is a symmetric-key block cipher. Once the files are saved in a respective technique, user will get LSB encrypted image through email. Which will act as key to access a particular file. Whenever user needs the file, user will upload the file and it will decrypt the file using the three techniques, and the user will get the file. When user needs to access the respective file, users should give document which will trigger the decryption process on the particular cryptography strategies and merge all the three files to its original file.
