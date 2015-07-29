# File-Upload-and-download-utility-for-Google-cloud

The program provides a utility that runs on your local device that allows

files in your local file system to be dropped into Google cloud storage, for added

safety those files should be encrypted, and after moving the encrypted file to Google

cloud it should be deleted from the local device and also we will be able to 

retrieve a file and decrypt it.

I used a (validated) single key encryption, such as AES, and each file 

have it’s own key (password) so the program prompts for that key/password.

The program is also able to list and remove files from your 

cloud storage. The encryption and Decryption is done both locally and on cloud.
