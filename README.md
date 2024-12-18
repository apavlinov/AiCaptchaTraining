# AiCaptchaTraining

```bash
git clone git@github.com:yrslvpvlnv/AiCaptchaTraining.git

# install python3.11
sudo apt-get install python3.11

# install pipenv
pip install pipenv

# create virtual environment
pipenv shell

# install all from requirements.txt
pipenv install -r requirements.txt

# run training & testing. See results in diagrams, model saved in file: captcha_ocr_model.h5
python captcha_ocr.py
```

Youtube origin: 
1. https://www.youtube.com/watch?v=3DZZJPQMYIY&ab_channel=TESSERACT 
2. https://github.com/DilerFeed/Neural-networks-and-AIs/tree/main/captcha_ocr

Origin Tutorial: 
- https://keras.io/examples/vision/captcha_ocr/
- https://github.com/keras-team/keras-io/blob/master/examples/vision/captcha_ocr.py

![fig.1](assets/Figure_1.png)
![fig.2](assets/Figure_2.png)
![fig.3](assets/Figure_3.png)

### NEXT: Run on CUDA
https://stackoverflow.com/questions/70306845/i-cant-train-my-nn-with-tensorflow-using-gpu