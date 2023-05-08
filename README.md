
<div align="center">
    <br> QualityScaler-Ginppai - 긴빠이된 image/video AI upscaler app (BSRGAN) <br><br>
    <a href="https://github.com/ccvv804/QualityScaler-Ginppai/releases">
         <img src="https://user-images.githubusercontent.com/86362423/162710522-c40c4f39-a6b9-48bc-84bc-1c6b78319f01.png" width="200">
    </a>
</div>

## 이 저장소는?
이 저장소는 [Djdefrag/QualityScaler](https://github.com/Djdefrag/QualityScaler)을 긴빠이 한것입니다. 언제 어디에서 누구나 손쉽게 QualityScaler를 긴빠이 할 수 있도록 편집되었지만 소스코드 수정은 없습니다.

### 긴빠이는?
긴빠이는 해병 문학에서 등장하는 단어로서 훔친다는 의미의 해병대 은어입니다. 일본어 ギンバエ에서 유례된 것으로 추정됩니다.

## Credits.
BSRGAN - https://github.com/cszn/BSRGAN | https://arxiv.org/abs/2103.14006

## Requirements.
- Windows 11 / Windows 10
    - DirectML 덕분에 리눅스나 맥은 안됩니다.
- RAM >= 8Gb
- Directx12 compatible GPU
    - 합리적인 사용을 위해서는 어느정도 성능이 되어야 합니다.
## How to install manually.
```sh
git clone https://github.com/ccvv804/QualityScaler-Ginppai
cd QualityScaler-Ginppai
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
python QualityScaler.py
```
## Features.
- [x] Easy to use GUI
- [x] Images and Videos upscale
- [x] Automatic image tiling and merging to avoid gpu VRAM limitation
- [x] Resize image/video before upscaling
- [x] Multiple Gpu support
- [x] Compatible images - png, jpeg, bmp, webp, tif  
- [x] Compatible video  - mp4, wemb, gif, mkv, flv, avi, mov, qt 

## How is made.
QualityScaler is completely written in Python, from backend to frontend. 
External packages are:
- AI  -> torch / torch-directml
- GUI -> customtkinter / win32mica
- Image/video -> openCV / moviepy
- Packaging   -> pyinstaller / upx
