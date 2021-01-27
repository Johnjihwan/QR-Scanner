# QR-Scanner [QR코드 인식 프로그램]
## ✅ Environment & Settings
**Install "zbar"**
```
brew install zbar
```
**Install "cv2"**
```
python -m pip install opencv-python
```
**Install "matplotlib"**
```
pip install matplotlib
```
**There will be an error like this**
```
TypeError: Image data of dtype object cannot be converted to float
```

**Solution**  
> Jupyter에 image를 미리 upload 해주면 됩니다.
```
from IPython.display import Image
 
Image("img/picture.png") # code안에서 나오게 할 때
```
