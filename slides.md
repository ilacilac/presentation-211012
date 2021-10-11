---
theme: unicorn
colorSchema: 'light'
layout: intro
introImage: 'public/cookie.png'
---
<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR&display=swap');
* {  
  font-family: 'Noto Sans KR', sans-serif;
}
h1 {
  padding-bottom: 1rem;
  margin-bottom: 1rem;
  border-bottom: 1px solid #dddddd;
}
.intro-p {
  margin-top: 1rem!important;
}
.my-auto {
  height: 100%;
}
.intro .my-auto,
.center .my-auto {
  height: auto;
}
</style>
# Cookie & Session
<p class="intro-p">연구개발본부 IT혁신팀 / Layla</p>
<!-- # 브라우저에서 쉽게 접하는 Cookie & Session -->
<style>
.p-1 {
  margin-top: 10px;
}
.flex-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
<!-- <div class="p-1">
사이트를 이용할 때 <br />
로그인하고 일정시간에 도달했을 때
</div> -->
---
layout: cover
---
# Cookie
<style>
.layout-center {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 50px;
}
</style>
<div class="layout-center">
  <img src="/cookies.png" width="200"><br />
  <p>쿠키는 브라우저/로컬에 저장되는 문자열 데이터</p>
</div>

```bash
# exmaple
cookie_name1=cookie_value1; cookie_name2=cookie_value2
```

---
layout: cover
---

# Cookie
- 이름, 값, 유효기간, 도메인, 경로, 유효기간으로 구성
- 클라이언트에 총 300개의 쿠키를 저장가능
- 하나의 도메인 당 20개의 쿠키
- 하나의 쿠키는 4KB까지 저장가능
- 쿠키를 이용해서 서버는 브라우저에 데이터를 넣을 수 있음
- 브라우저는 쿠키가 있으면 자동적으로 요청을 보냄
- 도메인에 따라 제한
- 인증 뿐만 아니라 여러정보를 담을 수 있음

---
layout: cover
---
# HTTP
<style>
.my-auto {
  margin: 0!important;
}
.section-2 {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  margin-top: 50px;
  
  .flex-column-2 {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 120px;
    margin-top: 1rem;
    /* font-weight: bold;
    font-size: 24px; */
    letter-spacing: -0.025px;
    text-align: center;
    color: #333333;

    img {
      display: block;
    }
  }
}

</style>
<div class="flex-wrap section-2">
  <div class="flex-column-2">
    <img src="/http1.png" /><br />
    <p>비연결성(Connectionless)</p>
  </div>
  <div class="flex-column-2">
    <img src="/http2.png" /><br />
    <p>무상태성(stateless)</p>
  </div>
</div> 

---
layout: cover
---
# HTTP
<div class="flex-wrap">
  <img src="/http3.png" /><br />
</div>

---
layout: cover
---
# HTTP
<div class="flex-wrap">
  <img src="/http4.png" /><br />
</div>

---
layout: cover
---
# HTTP
<div class="flex-wrap">
  <img src="/http5.png" /><br />
</div>

---
layout: cover
---
# HTTP
<div class="flex-wrap">
  <img src="/http6.png" /><br />
</div>

---
layout: cover
---
# HTTP
<div class="flex-wrap">
  <img src="/http7.png" /><br />
</div>

---
layout: cover
---
# HTTP
<div class="flex-wrap">
  <img src="/http8.png" /><br />
</div>

---
layout: cover
---
# HTTP
<div class="flex-wrap">
  <img src="/http9.png" /><br />
</div>

---
layout: cover
---
# Session
<div class="flex-wrap">
  <img src="/cookie-session.png" /><br />
</div>
---
layout: center
---

# 감사합니다 : )
