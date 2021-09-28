# likelion-naver
수업 자료 - 네이버 클라우드와 클로바를 활용한 인공지능 서비스 만들기 https://classlion.net/class/detail/22

## 목록
- 수업을 위한 프로그램 설치 가이드 - [chapter02 링크](ch02/pre-install.md) / [Chapter05,06 링크](ch05/requirement.md)
- 네이버 클라우드 플랫폼 서버 / 클라우드 펑션 사용 종료가이드 - [링크](ncp/ncp_server_terminate.pdf)

### [Chapter02 수업자료](ch02)
- 네이버 클라우드 플랫폼 서버 init script 설치용 파일 [링크](ch02/server_init.sh)
- 그 외 소스코드는 각 폴더에서 찾아보세요. [링크](ch02)
- cloud function용 zip 파일 [링크](ch02/saveNaverNews_ch02.zip) - 우측 상단 `Download` 버튼 클릭
- Python 설치해야하는 패키지 (pip 명령어)
    ```bash 
    pip install pymongo requests
    ```

### [Chapter03 수업자료](ch03)
- bootstrap theme 테마 템플릿 파일들 [링크](ch03/bootstrap-5.1.0-examples.zip)
- 그 외 소스코드는 각 폴더에서 찾아보세요. [링크](ch03)
- Python 설치해야하는 패키지 (pip 명령어)
    ```bash 
    pip install pymongo beautifulsoup4 requests flask 
    ```

### [Chapter04 수업자료](ch04)
- Python 설치해야하는 패키지 (pip 명령어)
  - flask 사용하는 웹 프로젝트가 아닐 경우에는 flask 를 빼고 설치하면 됩니다.
    ```bash 
    pip install pymongo beautifulsoup4 requests flask pytz
    pip install boto3==1.6.19
    ```
- 소스코드는 각 폴더에서 찾아보세요. [링크](ch04)


### [Chapter05 수업자료](ch05)
- Python 설치해야하는 패키지 (pip 명령어)
  - flask 사용하는 웹 프로젝트가 아닐 경우에는 flask 를 빼고 설치하면 됩니다.
    ```bash 
    pip install pymongo requests flask pytz
    pip install boto3==1.6.19
    ```
- [설치하기 및 사이트 모음](ch05/requirement.md)
- [서버 사용을 위한 기본 명령어 모음](ch05/server_command.md)
- [Flask에서 오디오 플레이 위한 기본 설정](ch05/audio_library.md)
- [index.html 코드 조각 모음](ch05/index_codesnippet.md)
- 소스코드는 각 폴더에서 찾아보세요. [링크](ch05)
  - 설정파일 configuration : /config_sample
  - Flask 프로젝트 : /heyvolleyballnews
  - 뉴스 요약 : /summary 
    - cloud function 용 압축파일 : /summary/summaryNews.zip 
  - 음성합성(오디오북) : /voice 
    - cloud function 용 압축파일 : /summary/voice.zip 

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="크리에이티브 커먼즈 라이선스" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />이 저작물은 <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">크리에이티브 커먼즈 저작자표시-비영리-동일조건변경허락 4.0 국제 라이선스</a>에 따라 이용할 수 있습니다.
