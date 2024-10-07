<template>
<div style="margin-left: 15px;">
<h1 style="font-family: Geologica; color: white; font-weight: normal;">Marketplace:</h1>
<input style="font-family: Geologica; font-weight: normal; font-size: 16px" placeholder="    Search..."><br>
<button class="job"><p style="font-family: Geologica; font-weight: normal; color: Black;">Jobs</p></button>
<button class="peop"><p style="font-family: Geologica; color: White; font-weight: normal;">People</p></button>
</div>

<div class="jobs1">
<img src="https://i.postimg.cc/FK8K0bcd/IMG-1157.png" style="width: 30px; margin-left: 15px; margin-top: 15px;">
<p style="font-family: Geologica; color: #97f492; font-size: 14px; margin-top: -32px; margin-left: 55px;">Jr. Game Designer</p><br>
<p style="font-family: Geologica; color: #8a8686; font-size: 12px; margin-top: -32px; margin-left: 55px; line-height: 1,1px;">Penza,Russia</p>
<p style="font-family: Geologica; color: #dbd7d7; line-height: 1,1%; margin-top: -10px; margin-left: 15px; font-size: 14px">It is important to pay attention to creating an atmospheric and intriguing game with an original plot and an attractive visual style.</p>
<p style="font-family: Geologica; color: #636060; margin-left: 15px; font-size: 12px; margin-top: -10px;">3 hours ago</p>
<p style="font-family: Geologica; color: #636060; font-size: 12px; margin-top: -27px; text-align: right; margin-right: 15px;">Viewed 1</p>
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
  height: 35px;
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
  height: 130px;
  border-radius: 20px;
  margin-top: 20px;
  margin-left: 15px;
  border: 1px solid white;
}

@media screen and (min-width: 375px) and (max-width: 404px) {
  input {
    width: 370px;
  }

  .job {
    width: 170px;
  }

  .peop {
    width: 170px;
    margin-left: 30px;
  }

  .jobs1 {
    width: 370px;
  }
}

@media screen and (min-width: 405px) and (max-width: 417px) {
input {
  width: 370px;
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
}
</style>
