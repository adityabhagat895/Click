<html>
<head>
	<title>Box</title>
	<link rel="icon" type="image/x-icon" href="https://www.pinclipart.com/picdir/big/204-2049921_cube-clipart-unix-png-download.png" />
<!--<link rel="stylesheet" media="screen and (max-width: 750px)" href="max-width 750.css">-->


	<style>
		html{
			height: 100%;
		}
         *{
         	box-sizing: border-box;

         }
         body{
         	
         	background-image: url('10.jpg');
         	background-size:cover;
		 background-repeat:no-repeat;
display: flex;
justify-content: center;
         	align-items: center;

         }
         
         #main{
         
         	perspective: 800px;
         	margin:200px;
         	
         }
         #img{
         	transform-style: preserve-3d;
         	width:300px;
         	height:300PX;
         	margin: auto;
         	animation: cube 15s infinite linear ;
         	position: relative;
         }
         @keyframes cube{
         	0%{
         		transform:rotateX(0deg) rotateY(0deg);
         	}
         	100%{
         		transform: rotateX(360deg) rotateY(360deg);
         	}
         	

         }
         #img  img{
         	position: absolute;
         	
         	opacity: 0.95;
         	width: 200px;
         	height: 200px;
         	border:4px solid black;
         }
		img:nth-child(1){
			transform:rotateY(0deg) translateZ(100px);
		}
		img:nth-child(2){
			transform:rotateY(90deg) translateZ(100px);
		}
		img:nth-child(3){
			transform:rotateY(180deg) translateZ(100px);
		}
		img:nth-child(4){
			transform:rotateY(-90deg) translateZ(100px);
		}
		img:nth-child(5){
			transform:rotateX(90deg) translateZ(100px);
		}
		img:nth-child(6){
			transform:rotateX(-90deg) translateZ(100px);
		}
		

#main2{
	display: flex;
         	justify-content: center;
         	align-items: center;
         	
         	width: 200px;
         	height: 200px;
         	transform-style: preserve-3d;
         	animation:slideShow  30s infinite linear ;
         	margin-top: 200px;
         	margin-bottom: 200px;	
	margin-left:50px;

         }
         @keyframes slideShow{
         	0%{
         		transform: perspective(800px) rotateY(0deg);
         	}
         	100%{
         		transform: perspective(800px) rotateY(360deg);
         	}
         	

         }
         #main2 span{
         	position: absolute;
         	transform-style: preserve-3d;
         	transform-origin: center;
         	width: 100%;
         	height: 100%;
         }
		span:nth-child(1){
			transform:rotateY(22.5deg) translateZ(200px);
		}
		span:nth-child(2){
			transform:rotateY(45deg) translateZ(200px);
		}
		span:nth-child(3){
			transform:rotateY(67.5deg) translateZ(200px);
		}
		span:nth-child(4){
			transform:rotateY(90deg) translateZ(200px);
		}
		span:nth-child(5){
			transform:rotateY(112.5deg) translateZ(200px);
		}
		span:nth-child(6){
			transform:rotateY(135deg) translateZ(200px);
		}
		span:nth-child(7){
			transform:rotateY(157.5deg) translateZ(200px);
		}
		span:nth-child(8){
			transform:rotateY(180deg) translateZ(220px);
}
		span:nth-child(9){
			transform:rotateY(202.5deg) translateZ(200px);
		}
		span:nth-child(10){
			transform:rotateY(225deg) translateZ(200px);
		}
		span:nth-child(11){
			transform:rotateY(247.5deg) translateZ(200px);
		}
		span:nth-child(12){
			transform:rotateY(270deg) translateZ(200px);
		}
		span:nth-child(13){
			transform:rotateY(292.5deg) translateZ(200px);
		}
		span:nth-child(14){
			transform:rotateY(315deg) translateZ(200px);
		}
		span:nth-child(15){
			transform:rotateY(337.5deg) translateZ(200px);
		}
		span:nth-child(16){
			transform:rotateY(360deg) translateZ(200px);
		}
span img{
	position: absolute;
	height: 50%;
	width: 50%;
}

	</style>
</head>
<body>
<div id="main">
	<div id="img">
	
		<img src="2.jpg">
	
	
		<img src="1.jpeg">
	
	 
		<img src="20.jpg">
	 
 
	<img src="9.jpg">
 
 
	<img src="21.jpg">
 
 
	
	<img src="20.jpg">
 
 
</div>

<div id="main2">
<span>
		<img src="4.jpg">
	</span>
	<span>
		<img src="5.jpg">
	</span>

	<span>
		<img src="25.jpg">
	</span>
<span>
	<img src="7.jpg">
</span>
<span>
	<img src="3.jpg">
</span>
<span>
	
	<img src="8.jpg">
</span>
<span>
	<img src="10.jpg">
</span>
<span>
	<img src="11.jpg">
</span>
<span>
		<img src="12.jpg">
	</span>
	<span>
		<img src="13.jpg">
	</span>

	<span>
		<img src="14.jpg">
	</span>
<span>
	<img src="15.jpg">
</span>
<span>
	<img src="16.jpg">
</span>
<span>
	
	<img src="23.jpg">
</span>
<span>
	<img src="24.jpg">
</span>
<span>
	<img src="19.jpg">
</span>
<audio autoplay loop> 
	<source src="bgm.mp3" type="audio/mp3">
</audio>
</div>


