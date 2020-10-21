<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link href="https://fonts.googleapis.com/css?family=Source+Code&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Montserrat+Subrayada&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Homemade+Apple&display=swap" rel="stylesheet">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bricken</title>
  </head>
  <body>

<div class="main">
  <img class="logo" img src="logo.png">
<h1>Bricken Media</h1>
</div>

<div class= "info">
<p>[Text] [Form] [Projekt] [Print] [www] [Flen]</p>

</div>

  <div class= "footer">
    <div class= "footer-content">
        <p-footer> ©BRICKEN.SE | <a href="mailto:sturen.ulrika@gmail.com" style="color:white">STUREN.ULRIKA@GMAIL.COM</a>  |
          <a href="https://twitter.com/bricken140" style="color:white">TWITTER</a> | <a href="https://se.linkedin.com/in/ulrika-sturén-a6314b48" style="color:white"> LINKEDIN</a>

        </p-footer>
    </div>
  </div>

</body>


<style>
body {
  margin: 0;
  background: url('background.png') no-repeat center;
  background-size: cover;
  background-position: top
}

html, body {
    max-width: 100%;
    overflow-x: hidden;
}

.main {
  margin: 0 auto;
  position: relative;
  display: flex;
  flex-direction:column;

}


.logo {
  height: 335px;
  padding: 0px;
  margin: 0 auto;
  margin-top: 100px;
  margin-bottom: 50px;
  align-items: center;


}

.footer{
  background-color: black;
  padding-bottom: 50px;

}

.footer-content{
  text-align: center;
  padding: 20px;
  padding-top: 40px;
}

.info{
  text-align: center;
  padding: 20px;
  padding-top: 40px;
}
p{
  font-size: 55px;
  line-height: 65px;
  color: #FFFFFF;
  font-family: 'Josefin sans' , sans-serif;
  font-weight: normal;
  margin-bottom: 30px;

}

p-footer{
  font-size: 20px;
  line-height: 30px;
  color: #FFFFFF;
  font-family: 'Josefin sans' , sans-serif;
  font-weight: normal;
  margin-bottom: 30px;
}

h1{
  font-size: 150px;
  line-height: 150px;
  color: #FFFFFF;
  font-family: 'Homemade Apple' , sans-serif;
  font-weight: bold;
  text-align: center;
}

@media screen and (max-width: 900px) {

  .main {
    width: 50vh;


  }

  p {
  font-size: 40px;
  line-height: 50px;
  margin-bottom: 20px;
}

h1{
  font-size: 80px;
  line-height: 70px;

}

.logo {
max-width: 250px;
width: auto;
height: auto;
padding: 0px;
margin: 0 auto;
margin-bottom: 50px;
margin-top: 150px;
align-items: center;


.info {
  padding: 20px;
  margin: 20px auto 0 auto;
}

.footer-content{
    padding: 20px;
}

p-footer{
  font-size: 15px;
  line-height: 25px;
  margin-bottom: 20px;
}

.desktop{
  display: none;
}

}

</style>
