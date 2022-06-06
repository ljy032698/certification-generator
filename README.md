# 인증서 생성기

엑셀 데이터를 불러와 인증서를 생성해주는 파이썬으로 제작한 프로그램

## 운영체제별 개발환경 설정 방법 (파이썬, git 설치 방법)

터미널을 열고 다음의 명령어를 실행한다.
``` sh
# mac 인 경우 ()
brew install pyenv
brew install git
pyenv install 3.10.4
pyenv global 3.10.4

# windwos의 경우
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
choco install python
choco install git

# android 인 경우
pkg install python
pkg install git
```

## 파이썬 라이브러리 설치

``` sh
pip install -r requirements.txt
```

## 스크립트 실행 방법

``` sh
python main.py
```

## 라이선스
- [MIT](/LICENSE)