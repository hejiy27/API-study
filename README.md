
# 1. API란??
## - 응용프로그램에서 사용할 수 있도록, 운영체제나 프로그래민 언어가 제공하는 기능을 제어할 수 있게 만든 인터페이스를 뜻함 (위키피티아 사전)
## - 프로그램과 또 다른 프로그램을 연결해주는 일종의 다리(쉽게 설명)

* pygments : 문자열을 읽고 특정 코드를 인식하여 코드별로 색깔을 입혀주는 라이브러리
* Django에서는 REST framework로 API를 만듬.

 # 2. Serializer (직렬화)
 ## - Serializer : 메모리상의 데이터를 파일 형태로 변화시켜 줌(파일저장, 전송)->메모리상의 데이터를 파이썬으로 가져온 후 가져온 데이터를 Json 형태로 바꿔서 클라이언트에게 전송해줌.
 ## - Dserializer : 클라이언트에게서 온 Json 데이터를 파이썬 객체(데이터)로 번역한 후 장고 모델로 변역 후 DB에 넣음
 
#  3. API 만드는 순서
* DB 모델링 -> Serializer (API를 만들기위해 모델 JSON 변환) -> view(웹에서 확인가능하게 view 코드작성) -> url 연결 -> 웹에서 확인

## models.py
![Book](https://user-images.githubusercontent.com/46435457/71803225-88bb4c00-30a3-11ea-96ad-a2f97c1cbb58.png)


## Serializer.py
![Serializers](https://user-images.githubusercontent.com/46435457/71803313-d041d800-30a3-11ea-84f4-95c23b4e0c88.png)


## views.py
![view](https://user-images.githubusercontent.com/46435457/71803314-d33cc880-30a3-11ea-9f66-7fe7a64723b7.png)


## url.py

![url](https://user-images.githubusercontent.com/46435457/71803584-85749000-30a4-11ea-897d-2d59138d050c.png)

## Wed 확인
![API](https://user-images.githubusercontent.com/46435457/71803596-8d343480-30a4-11ea-94f0-718d2a854d0c.png)

 



