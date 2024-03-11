# Image to text converter in Python
## Setup
### Install python and tesseract
```
sudo apt install python python-dev python3.6 python3.6-dev python-tk protobuf-compiler
sudo apt install python-pip python3-pip 
sudo apt-get install tesseract-*

Replaced above commands with below and tried in a dockerized ubuntu
    1  apt-get update -y
    2  apt install python3 -y
    *3  apt install python python-dev -y
    4  apt install python-tk protobuf-compiler -y
    *5  apt install python-pip python3-pip
    6  apt install python-pip
    7  apt install python3-pip
    8  pip3 --version
    9  apt-get install tesseract-*
   10  pip3 install --upgrade setuptools
   11  pip3 install pytesseract
   12  pip3 install tesseract
   13  pip3 install pillow
   14  python3 --version
   15  history
   16  ll
   17  cd home/
   18  ll
   19  wget https://raw.githubusercontent.com/BeanGreen247/Image-to-text-converter/master/imagetotextconversion.py
   20  apt install wget
   21  wget https://raw.githubusercontent.com/BeanGreen247/Image-to-text-converter/master/imagetotextconversion.py
   22  ll
   23  python3 imagetotextconversion.py
   24  wget https://i.stack.imgur.com/t3qWG.png
   25  ll
   26  python3 imagetotextconversion.py
   27  vi out.txt-eng.txt 
   28  apt install vim
   29  vi out.txt-eng.txt 


```
### Upgrade setuptools
```
pip3 install --upgrade setuptools
```
### Install the dependencies
```
pip3 install pytesseract
pip3 install tesseract
pip3 install pillow
```
## Language
To find your needed language make sure to look here https://github.com/tesseract-ocr/tesseract/wiki/Data-Files

## Tips on improving the output
* remove noise and useless information
* increase contract
* choose the right size
* get the best possible image quality
* higher text quality (bigger DPI like 1200 DPI)
## Usage
Download the app
```
wget https://raw.githubusercontent.com/BeanGreen247/Image-to-text-converter/master/imagetotextconversion.py
```
Launch the app
```
python3.6 imagetotextconversion.py
```
It will ask for the image file location so make sure to give the full path like shown
```
Type full path to image you want to convert to text:/home/beangreen247/Pictures/text1.png
```
Next it will ask for the language used in the document
```
Type the language of the scanned document (3 letter ID):eng
```
And lastly it will ask for the output file name
```
Type output file name:text1-output
```
The files name will be, in my case, text1-output-eng.txt

Hope you like it.
