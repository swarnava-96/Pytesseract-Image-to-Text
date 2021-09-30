# Pytesseract-Image-to-Text


### About: This library converts the the texts that are present in images to strings(texts). 


### Installation:
The Code is written in Python 3.7.3 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. I have used the following steps to install the entire set up:
1. Install tesseract from [here](https://github.com/UB-Mannheim/tesseract/wiki). You can download the 32 or 64 bit according to your system configuration. I have used the 64 bit version. By default teserract get saved into ```"C:\Program Files\Tesseract-OCR"```. This is required for setting the path variable inside ```pytesseract.pytesseract.tesseract_cmd```
2. Create a virtual environment by using this command:
```conda create -n myenv python=3.7```
3. Activate the environment using the below command:
```conda activate myenv```
4. Install OpenCV as this will help to display the images:
```pip install opencv-python```
5. Install Pytesseract:
```pip install pytesseract```

Now,you are good to go. For more details click [here](https://github.com/UB-Mannheim/tesseract/wiki).



