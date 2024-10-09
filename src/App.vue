<template>
  <div style="margin-left: 15px;">
  <h1 style="font-family: Geologica; color: white; font-weight: normal; font-size: 26px;">Marketplace:</h1>
  <input style="font-family: Geologica; font-weight: normal; font-size: 16px" placeholder="  Search..."><br>
  <button class="job"><p style="font-family: Geologica; font-weight: normal; color: Black; font-size: 16px; margin-top: 5px;">Jobs</p></button>
  <button class="peop"><p style="font-family: Geologica; color: White; font-weight: normal; font-size: 16px; margin-top: 5px;">People</p></button>
  </div>
  
  <div class="jobs1">
  <img src="https://i.postimg.cc/FK8K0bcd/IMG-1157.png" style="width: 30px; margin-left: 15px; margin-top: 15px;">
  <p style="font-family: Geologica; color: #97f492; font-size: 14px; margin-top: -32px; margin-left: 55px;">Jr. Game Designer</p><br>
  <p style="font-family: Geologica; color: #8a8686; font-size: 12px; margin-top: -32px; margin-left: 55px; line-height: 1,1px;">Penza,Russia</p>
  <p style="font-family: Geologica; color: #dbd7d7; line-height: 1,1%; margin-top: -10px; margin-left: 15px; font-size: 14px">It is important to pay attention to creating an atmospheric and intriguing game with an original plot and an attractive visual style.</p>
  <p style="font-family: Geologica; color: #636060; margin-left: 15px; font-size: 12px; margin-top: -10px;">3 hours ago</p>
  <p style="font-family: Geologica; color: #636060; font-size: 12px; margin-top: -27px; text-align: right; margin-right: 15px;">Viewed 1</p>
  </div>

  <div class="bottom" style="margin-left: 15px; font-color: black;">
  <button class="profile"><p style="margin-top: 5px; color: black;">Profile</p></button>
  <button class="market"><p style="margin-top: 5px; color: black;">Marketplace</p></button>
  <button class="message"><p style="margin-top: 5px; color: black;">Messages</p></button>
  </div>
</template>
  
<style>
  body {
    background-color: #101622;
    font-weight: normal;
  }
  
  input {
    background-color: #272e38;
    border-radius: 25px;
    height: 30px;
    width: 400px;
    border-color: white;
    border-width: 1px;
  }
  
  .job {
    background-color: #97f492;
    width: 180px;
    height: 35px;
    border-radius: 25px;
    border-color: white;
    border-width: 1px;
    margin-top: 15px;
  }
  
  .peop {
    background-color: #272e38;
    width: 180px;
    height: 35px;
    border-radius: 25px;
    border-color: white;
    border-width: 1px;
    margin-top: 15px;
    margin-left: 40px;
  }
  
  .jobs1 {
    background-color: #272e38;
    width: 400px;
    height: 135px;
    border-radius: 20px;
    margin-top: 20px;
    margin-left: 15px;
    border: 1px solid white;
  }

  .bottom {
    background-color: white;
    width: 400px;
    height: 50px;
    border-radius: 15px;
    margin-top: 300px;
    position: fixed;
  }

  .profile {
    background-color: white;
    border-radius: 18px;
    width: 80px;
    height: 30px;
    margin-top: 10px;
    margin-left: 15px;
    border: 1px solid black;
    font-family: Geologica;
  }

  .market {
    background-color: #97f492;
    border-radius: 18px;
    width: 120px;
    margin-top: 10px;
    height: 30px;
    margin-left: 15px;
    border: 1px solid black;
    font-family: Geologica;
  }

  .message {
    background-color: white;
    border-radius: 18px;
    width: 100px;
    height: 30px;
    margin-top: 10px;
    margin-left: 15px;
    border: 1px solid black;
    font-family: Geologica;
  }

  @media screen and (width: 390px) {
    input {
      width: 345px;
    }

    .job {
      width: 170px;
    }

    .peop {
      width: 170px;
      margin-left: 10px
    }

    .jobs1 {
      width: 345px;
    }

    .bottom {
      width: 345px;
    }

    .message{
      width: 100px;
      margin-left: 10px;
    }

    .profile {
      margin-left: 12px;
    }

    .market {
      margin-left: 10px
    }
  }
  
  @media screen and (min-width: 405px) and (max-width: 417px) {
  input {
    width: 360px;
  }
  
  .job {
    width: 180px;
  }
  
  .peop {
    width: 180px;
    margin-left: 15px;
  }
  
  .jobs1 {
    width: 370px;
  }

  .bottom {
    width: 360px;
    margin-top: 350px;
  }
}

  @media screen and (width: 375px) {
    input {
      width: 330px;
    }

    .job {
      width: 160px;
    }

    .peop {
      width: 160px;
      margin-left: 18px;
    }

    .jobs1 {
      width: 330px;
    }

    .bottom {
      width: 330px;
    }

    .message{
      width: 85px;
      margin-left: 10px;
    }

    .profile {
      margin-left: 12px;
    }

    .market {
      margin-left: 10px
    }
  }

  @media screen and (width: 393px) {
    input {
      width: 350px;
    }

    .job {
      width: 170px;
    }

    .peop {
      width: 170px;
      margin-left: 15px;
    }

    .jobs1 {
      width: 350px;
    }

    .bottom {
      width: 350px;
    }

    .profile {
      margin-left: 10px;
    }
  }

  @media screen and (width: 430px) {
    input {
      width: 380px;
    }

    .job {
      width: 170px;
    }

    .peop {
      width: 170px;
    }

    .jobs1 {
      width: 380px;
    }

    .bottom {
      width: 380px;
    }

    .message{
      width: 100px;
    }

    .profile {
      margin-left: 20px;
    }

    .market {
      margin-left: 15px;
    }
  }
  </style>
