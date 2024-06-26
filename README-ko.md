# YouTube Music Downloader

Youtube 영상 링크를 주면, 사운드를 추출하는 콘솔 프로그램입니다.

# Library
- yt-dlp (youtube-dl)
- pytube (search)
- pillow (thumbnail)
- pydub (split the music)
- pathvalidate

# Download
GitHub Releases를 통해서 다운로드할 수 있습니다.
> [Download Link](https://github.com/ktnoxs/YoutubeMusic/releases)

# Run

### 1. Setup
```bash
pip install -r requirements.txt
```

### 2. Install ffmpeg

ffmpeg를 다운받고 `Youtube Music Downloader.exe`가 있는 폴더 안에 ffmpeg 폴더를 생성한 후, 폴더 안에 `ffmpeg.exe`, `ffplay.exe`, `ffprobe.exe`파일을 넣어주세요.
<br><br>
혹은 환경변수에 ffmpeg 경로(`bin`)를 등록해주시면 됩니다.

### 3. Run

`Youtube Music Downloader.exe`를 실행합니다.
영상 링크를 줘도 되고, 플레이리스트 링크도 입력 가능합니다. 또는 텍스트 파일로 링크를 입력한 뒤, 해당 텍스트파일을 입력하면 자동으로 다운로드 됩니다. 유튜브에 검색하듯이 입력도 가능합니다.

# Build

`python build.py`을 통해 빌드할 수 있습니다. 결과물은 `output` 폴더에 생성됩니다.