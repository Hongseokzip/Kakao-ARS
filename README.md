# KakaoTalk-Bot-Boilerplate

- virtualenv 설정
``` sh
$ virtualenv -p /usr/bin/python venv
```
- google cloud sdk 다운로드 및 설치
``` sh
$ cd venv/
$ curl https://sdk.cloud.google.com | bash
```
> google-cloud-sdk 경로 설정 입력 시, . 으로 입력

> PATH 설정 여부 Y

> Enter a path to an rc file to update... 입력은 bin/activate 로 입력

> 현재 쉘을 재시작

``` sh
$ (venv) gcloud init
```

참고<br>
[VirtualEnv 에 Google Cloud SDK 설정하기](https://jeonsungyun.github.io/2017/python-google-cloud-sdk-virtualenv-setting/) <br>
[Flask RESTful 라이브러리와 Blueprint](https://jeonsungyun.github.io/2017/flask-restful-with-blueprint/)
