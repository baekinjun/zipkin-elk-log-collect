# โจ BTS (Bithumb NTF SNS) ๐ฐ

## ๋ด๋น์ ๋ฐฑ์ธ์ค

## ๐ ํ๋ก์ ํธ ์๊ฐ

- ํ๋ก์ ํธ๋ช์ **Bithumb์ NFT์ SNS ์๋น์ค๋ฅผ ๊ฒฐํฉํ์ฌ BTS๋ก ์ง์์ต๋๋ค.** ๋ค์ํ ์๊ฐ๋ค์ ๊ทธ๋ฆผ๊ณผ ์ํธ๋ฅผ NFT ์ฝ์ธ ๊ฒฝ๋งค๋ก ๋ง๋๋ณผ ์ ์์ผ๋ฉฐ ๋น์ธ ์ฝ์ธ ์ ์ ๋ค๊ณผ ์ด๋ฆฐ ์ํต์ ํ  ์ ์๋๋ก SNS ์ปค๋ฎค๋ํฐ๋ ํ์ฑํ ์์ผฐ์ต๋๋ค.

## log ์๋ฒ 

zipkin : http://3.38.28.154:9411

kibana: http://13.125.84.58:5601/app/discover


## log ๊ตฌ์ฑ๋ 

![log](https://user-images.githubusercontent.com/58027908/136663497-4eba35e5-73d3-4232-9b18-cc5efd7396ac.png)

beats ๋ ์์ป์ต๋๋ค .

1. spring ์๋ฒ ๋ก๊ทธ ๋ฐ์
2. ๋ฐ์๋ ๋ก๊ทธ logstash ๋ก์ ๋ฌ
3. ์ ๋ฌ๋ฐ์ ๋ก๊ทธ elasticsearch ์ ์ ์ฅ

1. spiring ์๋ฒ ๋ก๊ทธ ๋ฐ์
2. zipkin ์์ ์ด๋์์ ๋ฐ์๋ฌ๋์ง ์ถ์ 
3. ์ถ์ ํ ๋ก๊ทธ๋ฅผ elasitcsearch ์์ ์ฅ

์ดํ ์ ์ฅ๋ ๋ก๊ทธ๋ฅผ kibana ์์ ์ธ๋ฑ์ฑํ๊ณ  ํ์ธํ ์์๋ค.



