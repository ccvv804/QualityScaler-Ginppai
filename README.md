
<div align="center">
    <br> QualityScaler-Ginppai - 긴빠이된 image/video AI upscaler app (BSRGAN) <br><br>
    <a href="https://github.com/ccvv804/QualityScaler-Ginppai/releases">
         <img src="https://user-images.githubusercontent.com/86362423/162710522-c40c4f39-a6b9-48bc-84bc-1c6b78319f01.png" width="200">
    </a>
</div>

## Credits.
BSRGAN - https://github.com/cszn/BSRGAN | https://arxiv.org/abs/2103.14006

## How is made.
QualityScaler is completely written in Python, from backend to frontend. 
External packages are:
- AI  -> torch / torch-directml
- GUI -> customtkinter / win32mica
- Image/video -> openCV / moviepy
- Packaging   -> pyinstaller / upx

## Requirements.
- Windows 11 / Windows 10
- RAM >= 8Gb
- Directx12 compatible GPU:
    - any AMD >= Radeon HD 7000 series
    - any Intel HD Integrated >= 4th-gen core
    - any NVIDIA >=  GTX 600 series

## Features.
- [x] Easy to use GUI
- [x] Images and Videos upscale
- [x] Automatic image tiling and merging to avoid gpu VRAM limitation
- [x] Resize image/video before upscaling
- [x] Multiple Gpu support
- [x] Compatible images - png, jpeg, bmp, webp, tif  
- [x] Compatible video  - mp4, wemb, gif, mkv, flv, avi, mov, qt 
