# ✨ BTS (Bithumb NTF SNS) 💰

## 담당자 백인준

## 👉 프로젝트 소개

- 프로젝트명은 **Bithumb의 NFT와 SNS 서비스를 결합하여 BTS로 지었습니다.** 다양한 작가들의 그림과 아트를 NFT 코인 경매로 만나볼 수 있으며 빗썸 코인 유저들과 열린 소통을 할 수 있도록 SNS 커뮤니티도 활성화 시켰습니다.

## log 서버 

zipkin : http://3.38.28.154:9411

kibana: http://13.125.84.58:5601/app/discover


## log 구성도 

![log](https://user-images.githubusercontent.com/58027908/136663497-4eba35e5-73d3-4232-9b18-cc5efd7396ac.png)

beats 는 안썻습니다 .

1. spring 서버 로그 발생
2. 발생된 로그 logstash 로전달
3. 전달받은 로그 elasticsearch 에 저장

1. spiring 서버 로그 발생
2. zipkin 에서 어디에서 발생됬는지 추적
3. 추적한 로그를 elasitcsearch 에저장

이후 저장된 로그를 kibana 에서 인덱싱하고 확인할수있다.



