- ๐ Hi, Iโm @chojaechun
- ๐ Iโm interested in ...
- ๐ฑ Iโm currently learning ...
- ๐๏ธ Iโm looking to collaborate on ...
- ๐ซ How to reach me ...

<!---
chojaechun/chojaechun is a โจ special โจ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

๏ปฟ


Java spring framework ( Version. 3.2.9 )

: Spring Boot ๋ฅผ ์ฌ์ฉํ๊ณ  ์์ง๋ ์์ง๋ง, Control, Service, dao์ bean์ ํ๋ํ๋ ์ค์ ํจ์ผ๋ก์

๊ธฐ๋ณธ์ ์ธ ๊ท์น์ ์ดํด ์ค


Common์ ์ํด์๋ Constants ๋ฅผ ์ดํดํ๋๋ก ํด๋ณด์

Bundle Plugin ์ค์ ์ Web modules์ Deployment Assembly์ ์ ์ ์ค์ ์ด ๋์ด์๋์ง ์ฒดํฌ ( ๋ฐฐํฌ์์ properties ์ ํฌํจ๋์ด์๋์ง๋ ์ฒดํฌ )

๊ฐ๋ฐ ํ์์ ์ฐ์  ํ์ฌ์์ ์ถ๊ตฌํ๋ ๊ฐ๋ฐ ๋ก์ง์ ์ดํดํ๋๊ฒ ์ค์


2021. 10 ~ 

React ๊ฐ๋ฐ์ ์งํ ์ค 

Version : 
  React : 17.0.2
  Mobx : 6.3.7
  framework7 : 6.3.9
  axios : 0.24.0
  vite : 2.6.14
  
  
  
ํ์ฌ ํน์ด ์ฌํญ

  Mobx์ Commponent ๊ด๋ฆฌ๊ฐ ์๋๋ ๊ฒ ๊ฐ๋ค. ( observerble, computed, action )
    observable : State์ ์ํ๋ฅผ ๊ฐ์ํ๋ค. <br>
    computed : State์ ์ ๋ณด๊ฐ ๋ณ๊ฒฝ๋๋ฉด ๊ทธ ๊ฐ์ ์ ์ฅํ๊ณ  ๋ค๋ฅธ ์ ๋ณด๋ก ๋ณ๊ฒฝ๋ ๋๊น์ง ๊ทธ ๊ฐ์ ๊ฐ๊ณ ์๋๋ค. <br>
    action : State๋ action์์๋ง ๋ณ๊ฒฝํ์ฌ์ผ ์ ๋๊ฐ์ง๋ฅผ ์ฌ์ฉํ์ฌ ํจ๊ณผ์ ์ผ๋ก State๋ฅผ ๊ด๋ฆฌ ํ  ์ ์๋ค. <br>


2021. 10 ~ 11 
  Mobx6 ๋ก ๋ณ๊ฒฝ ๋๋ฉด์ decorators๊ฐ ๋น ์ง๊ฑธ ๋ค๋ฆ๊ฒ ์๊ฒ ๋์๋ค.. <br>
    ( ๊ณต์ ๋ฌธ์์๋ ์๋ฐ์คํฌ๋ฆฝํธ์ ์ ์ ๊ธฐ๋ฅ์ด ์๋๋ผ์ ์ ์ ๊ธฐ๋ฅ์ด ๋ ๋๊น์ง ์ง์ํ๋ค๊ณ  ํ๋ค.. ) <br>
  ์ต์ง๋ก ๋ฐ์ฝ๋ ์ดํฐ๋ฅผ ์ฌ์ฉํ๊ฒ ๋ง๋ค์์ง๋ง, ์ ์๋๋ก ์ฌ์ฉํ๋๊ฒ ๋ง๋๊ฑฐ ๊ฐ์์ ์ ๋ถ ๋ณ๊ฒฝ..<br>
  
  
2021. 12 ~ ํ์ฌ
  Java Spring MVC ํจํด ์ฒ๋ผ ๊ตฌํ ํด๋ณด๋ ค ๋ธ๋ ฅ ์ค<br>
  Model - getter, setter ๊ตฌํ ( ๋ณ์์๋ observable, getter์๋ computed๋ฅผ ์ค์  )<br>
  Repository - Like DAO<br>
  Store - Control and Service<br>
  
  Store์์  Data converting ์ ํ๋ คํ์ผ๋.. <br>
  observable๋ก ๊ด๋ฆฌํ๊ธฐ ์ํด์๋ Store์์ ๊ด๋ฆฌํ๋๊ฒ ํธํ๋ค๊ณ  ํ๋จ,<br>
  ๋ณ์๋ฅผ ์ค์ ํ๊ณ  ํด๋น ๋ณ์๋ฅผ observable๋ก ์ค์ <br>
  
  ์๋ฌธ.. <br>
  ์๋ฒ์์ ๋ฐ์ ๋ฐ์ดํฐ๋ค ( Model list )์ Listํ ํ์ฌ observable, computed๋ก ์ค์ , ๋ฐ์ดํฐ๋ฅผ ๊ด๋ฆฌํ๋๋ฐ<br>
  ์ด๊ฒ ๋ง๋๊ฑด์ง... ( State๊ฐ ๋ณ๊ฒฝ๋ ๋๋ง๋ค ํ๋ฉด์ ์ ์์ ์ผ๋ก ๋น๋๊ธฐ ๋ณ๊ฒฝ๋๊ธด ํจ.. )<br>
  
๏ปฟ
