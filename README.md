This python code will help to encyrpt and decrypt password along with an option which will help generate randowm passwords as well. 
#Password_encrypt_decrypt.py -e
- output
	Password encryption/decryption tool
	Encryption option invoked
	Password encryption completed
	
#Password_encrypt_decrypt.py -d
- output
	Password encryption/decryption tool
	Decryption option invoked
	Your password - ['testing']
#Password_encrypt_decrypt.py -h
- output
Password encryption/decryption tool
usage: main.py [-h] [-e] [-d] [-r]

optional arguments:
  -h, --help     show this help message and exit
  -e, --encrypt  [Encrypt password]
  -d, --decrypt  [Decrypt password]
  -r, --random   [Random password]
  
#Password_encrypt_decrypt.py -r
- output
	Password encryption/decryption tool
	Random password generator

	Enter Length of the password to be generated: MIN 12 & MAX 18 :14
	w@0Xy*F{5_-f>j


Note: you need to update "passdir_path" per your requirement and also create a file with password in the name "mypassword", 
this is the file from where password will be taken for encryption and the same will be deleted post encryption.
