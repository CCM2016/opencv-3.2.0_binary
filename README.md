## Summary
- [OpenCV 3.2.0](https://github.com/opencv/opencv)
  - with [opencv_contrib](https://github.com/opencv/opencv_contrib) modules
  - with [Tesseract 4.0.0a](https://github.com/tesseract-ocr/tesseract) support (*need to install separately*)
  - without CUDA support
  - with OpenCV documents, (*~\doc\html\index.html*)
  - with OpenCV example programs binary (*~\samples*)
  - with OpenCV tutorial programs binary (*~\x64\vc14\samples*)
- Python 2.7.12 / [Anaconda 64-bit](https://www.continuum.io/)
- Windows 64-bit (*Only tested on Windows 10, likely works on Windows 7*)
- Compiled by Visual Studio 2015 


## Installation
1. Download *win_x64/OpenCV-3.2.0-AMD64.exe*
2. Install OpenCV to *C:\Program Files\OpenCV 3.2.0*
3. Copy *C:\Program Files\OpenCV 3.2.0\python\2.7\x64\cv2.pyd* to Python's *lib\site-packages* directory
4. Add Windows Environment *OPENCV_DIR* = *C:\Program Files\OpenCV 3.2.0\x64\vc14*


## Verify OpenCV
```sh
import cv2
print cv2.__version__

*output:*
3.2.0
```




*update on March 4, 2017*