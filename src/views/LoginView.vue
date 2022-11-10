<template>
  <div class="wrap">
      <div class="loginbody">
          <img src="../assets/imgs/logo.png">
          <div id="error"></div>
          <input id="userloginid" placeholder="아이디">
          <input type="password" id="userloginpw" placeholder="비밀번호">
          <button id="userloginbutton">로그인</button>
          <div id="loginformhelp">
              <button>아이디 찾기</button>
              <button>비밀번호 찾기</button>
          </div>
      </div>
  </div>
</template>

<script>
export default{}
</script>

<style>
*{
    margin: 0px;
    padding: 0px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.wrap{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
}
.loginbody{
    width: 450px;
    height: 700px;
    padding-top: 100px;
}
.loginbody>img{
    width: 400px;
    margin-left: 25px;
    margin-right: 25px;
}
#error{
    width: 450px;
    height: 30px;
    margin-top: 100px;
    font-size: 20px;
    color: red;
    padding-left: 20px;
    margin-bottom: 10px;
}
.loginbody>input{
    width: 415px;
    height: 50px;
    margin-bottom: 20px;
    padding-left: 30px;
    font-size: 20px;
    border: 2px solid #EEEEEE;
    background-color: #EEEEEE;
    border-radius: 25px;
}
#userloginbutton{
    border: 2px solid #3A4CA8;
    width: 450px;
    height: 50px;
    border-radius: 25px;
    font-size: 20px;
    color: #FAFAFA;
    background-color: #3A4CA8;
    cursor: pointer;
}
#loginformhelp{
    display: flex;
    justify-content: space-around;
    margin-top: 30px;
    margin-bottom: 50px;
}
#loginformhelp>button{
    font-size: 20px;
    color: grey;
    background-color: white;
    border: 0px;
    outline: 0px;
    cursor: pointer;
}
#pwerror{
    font-size: 20px;
    color: red;
}
</style>

