<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>2023 countdown</title>
  <link rel="shortcut icon" type="image/jpg" href="NY.png"/>
  <link href="https://w.wallhaven.cc/full/3z/wallhaven-3z32j3.jpg" mce_href="favicon.ico" rel="icon" type="image/x-icon"/>
  <style>
      @import url("https://fonts.googleapis.com/css?family=Poppins&display=swap");
* {
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
}
@media screen and (min-width: 1025px) {
  body {
   background: linear-gradient(to bottom right, #50a3a2 0,#78cc6d 100%);
    background-attachment: fixed;
    background-blend-mode: hard-light;
  }

  .container {
    width: 80%;
    margin: 5% auto;
    padding: 11% 5%;
    background-attachment: fixed;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    background: linear-gradient(to bottom right, #50a3a2 0,#78cc6d 100%);
  }

  .container h2 {
    text-align: center;
    font-size: 10em;
    line-height: 0.7em;
    color: #fff;
    margin-top: -80px;
  }

  .container h2 span {
    display: block;
    font-weight: 400;
    letter-spacing: 6px;
    font-size: 0.2em;
  }

  .countdouwn {
    display: flex;
    margin-top: 50px;
  }

  .countdouwn div {
    position: relative;
    width: 100px;
    height: 100px;
    line-height: 100px;
    text-align: center;
    background: #333333;
    color: #ffffff;
    margin: 0 15px;
    font-size: 3em;
    font-weight: 500;
  }

  .countdouwn div:before {
    content: "";
    position: absolute;
    bottom: -30px;
    left: 0;
    width: 100%;
    height: 35px;
    background: #ff0;
    color: #333;
    font-size: 0.35em;
    line-height: 35px;
    font-weight: 300;
  }

  .countdouwn #day:before {
    content: "Days";
  }

  .countdouwn #hour:before {
    content: "Hours";
  }

  .countdouwn #minute:before {
    content: "Minutes";
  }

  .countdouwn #second:before {
    content: "Seconds";
  }
}

.bubble-container{
     position: absolute;
     width: 100%;
     height: 100%;
     z-index: 0;
     overflow: hidden;
     top:0;
     left:0;
}

.bubble-container .bubble{
     position: absolute;
     bottom: -10rem;
     width:  4rem;
     height: 4rem;
     background-color: #f1f1f1;
     border-radius: 50%;
     opacity: .5;
     animation: rise 10s infinite ease-in;
}

.bubble-container .bubble-1 {
     width: 4rem;
     height: 4rem;
     left: 10%;
     animation: 8s;
}

.bubble-container .bubble-2 {
     width: 2rem;
     height: 2rem;
     left: 20%;
     animation-duration: 5s;
     animation-delay: 1s;
}

.bubble-container .bubble-3 {
     width: 5rem;
     height: 5rem;
     left: 35%;
     animation-duration: 7s;
     animation-delay: 2s;
}

.bubble-container .bubble-4 {
     width: 8rem;
     height: 8rem;
     left: 50%;
     animation-duration: 11s;
     animation-delay: 0s;
}

.bubble-container .bubble-5 {
     width: 3.5rem;
     height: 3，5rem;
     left: 55%;
     animation-duration: 6s;
     animation-delay: 1s;
}

.bubble-container .bubble-6 {
     width: 4.5rem;
     height: 4，5rem;
     left: 65%;
     animation-duration: 8s;
     animation-delay: 3s;
}

.bubble-container .bubble-7 {
     width: 9rem;
     height: 9rem;
     left: 75%;
     animation-duration: 12s;
     animation-delay: 2s;
}

.bubble-container .bubble-8{
     width: 2.5rem;
     height: 2.5rem;
     left: 80%;
     animation-duration: 6s;
     animation-delay: 2s;
}


@keyframes rise {
     0% {
         bottom: -10rem;
         transform: translateX(0); 
     }
     50% {
         transform: translate(10rem);
     }
     100%{
         bottom: 1080px;
         transform: translateX(-20rem);
     }
}

@media screen and (max-width:1024px){
  *{
    margin: 0;
    padding: 0;
  }
  body {
   background: linear-gradient(to bottom right, #50a3a2 0,#78cc6d 100%);
    background-attachment: fixed;
    background-blend-mode: hard-light;
  }
  .container{
    width: 100%;
    margin: 20% 0;
    padding: 0%;
   background: linear-gradient(to bottom right, #50a3a2 0,#78cc6d 100%);
  }
  .container div{
    margin: 0;
    color: #fff;
    line-height: normal;
  }
  .container h2 span{
    color:#fff;
    display: block;
    text-align: center;
    font-size: 1em;
  }
  .container h2:first-child div{
    font-size: 6em;
    text-align: center;
    margin: 10% 0;
  }

  .countdouwn{
    display: flex;
    justify-content: space-around;
    margin: 0;
     border-radius: 15px;
  }
  .countdouwn div{
    width: 20%;
    height: 13vw;
    margin: 0 10px;
    line-height: 13vw;
    font-size: 2.3em;
    position: relative;
    text-align: center;
    background: #333333;
    color: #ffffff;
    font-weight: 500;
    border-radius: 5px;
  }
  .countdouwn div:before{
    content:'';
    position: absolute;
    bottom: -30px;
    left: 0;
    width: 100%;
    height: 30px;
    background:  #ff0;
    color: #333;
    font-size: .35em;
    line-height: 35px;
    font-weight: 300;
     border-radius: 5px;
  }
  .countdouwn #day:before{
    content: 'Days';
     border-radius: 5px;
  }
  
  .countdouwn #hour:before{
    content: 'Hours';
  }
  
  .countdouwn #minute:before{
    content: 'Minutes';
  }
  
  .countdouwn #second:before{
    content: 'Seconds';
  }
}

      
  </style>
</head>

<body>
<div class="bubble-container">
	<div class="bubble bubble-1"></div>
	<div class="bubble bubble-2"></div>
	<div class="bubble bubble-3"></div>
	<div class="bubble bubble-4"></div>
	<div class="bubble bubble-5"></div>
	<div class="bubble bubble-6"></div>
	<div class="bubble bubble-7"></div>
	<div class="bubble bubble-8"></div>
</div>
	
  <div class="container">
    <h2>
      <span>Countdown to new year </span>
      <div id="Year">NA</div>
    </h2>
    <div class="countdouwn">
      <div id="day">NA</div>
      <div id="hour">NA</div>
      <div id="minute">NA</div>
      <div id="second">NA</div>
    </div>
  </div>
  <script>
    // 自动为下一年
    function newYear() {
      var Y = new Date().getFullYear() + 1
      var newDay = Y + '/1/1 00:00:00'
      var countDate = new Date(newDay);
      var now = new Date().getTime()
      gap = countDate - now;
      var second = 1000
      var minute = second * 60
      var hour = minute * 60
      var day = hour * 24

      var d = Math.floor(gap / day)
      var h = Math.floor((gap % day) / hour)
      var m = Math.floor((gap % hour) / minute)
      var s = Math.floor((gap % minute) / second)

      // 此处可删除
      d = addZero(d)
      h = addZero(h)
      m = addZero(m)
      s = addZero(s)
      // func end

      // 显示的年
      document.getElementById('Year').innerText = Y

      // 倒计时
      document.getElementById('day').innerText = d
      document.getElementById('hour').innerText = h
      document.getElementById('minute').innerText = m
      document.getElementById('second').innerText = s
    }

    // 数字小于10前面就加0
    function addZero(num) {
      return num < 10 ? '0' + num : num
    }

    setInterval(() => {
      newYear()
    }, 1000)
  </script>
</body>

</html>


