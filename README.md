# Spam-Hound - interface to detect recieved sms if fake or not
### Demo: [Youtube](#main)

## Requirements (installable via pip)
- [numpy](https://pypi.org/project/numpy/)
- [imageio](https://pypi.org/project/imageio/)
- [multipledispatch](https://pypi.org/project/multipledispatch/)
- [Pillow](https://pypi.org/project/Pillow/)
- [opencv-python](https://pypi.org/project/opencv-python/)

## What I used?
1. [pycrypto](https://docs.python.org/3/library/crypto.html) - for Cryptography based encryption - It is used to encrypt and decrypt data into secured unreadable form. 
2. [opencv2](https://opencv.org/) - for Steganography - It is used for image and video manipulation. We used it for embedding encrypted data into images/videos.
3. [rsa](https://stuvel.eu/python-rsa-doc/usage.html) - for RSA based encryption - RSA is a asymmetric encryption method, used for encrypting data.


## How to run the program?
1. **Download this GitHub repository**
	- Either Clone the repository
		```
		git clone https://github.com/HarshPatel0x07/Spam-Hound.git
		```
	- Or download and extract the zip archive of the repository.

2. **Download & Install requirements**
	- Ensure that you have Python 3 installed.
	- Open terminal in the Repository folder on your local machine.
	- Run the following command to install requirements.
		```
		pip install -r requirements.txt
 		```
3. **Run the Program**
	```
	python main.py
	```
	*Expected Interface:*
	<br><img src="lib/images/main_screen.png?raw=true">
4. **Enter your Spam**
   - Generate Result.

