<!DOCTYPE html>
<html>
<head>
	<title>profile</title>
	<link rel="icon" href="126471.svg"/>
	<meta name="viewport" content='width-device-width,initial-scale=1' />
	<style >
		.parent{
			align-items: center;
			background: #fff;
			border: 5px solid rgb(3,123,145);
			padding: 1%;
			margin: 1%;
			width: 100%;
			flex-direction: column;
			justify-content: center;
			

		}
		.child{
			background: #fff;
			border: 5px solid rgb(3,123,145);
			padding: 1%;
			margin: 1%;
			width: 30%;
			flex-direction: row
			justify-content:center;
		}
		.child2{
			background: #fff;
			border: 5px solid rgb(3,123,145);
			padding: 1%;
			margin: 1%;
			width: 60%;
			flex-direction: row;
			justify-content: center;
		}
		/* small scale devices */
		@media only screen and (min-width:320px) and (max-width: 480px){
				.child{
					width: 40%;
					font-size: 25px;
					background: yellow;
				}

		}
		@media only screen and (min-width: 481px)and (max-width: 767px){
				.child{
					width: 40%;
					font-weight:600;
					border:3px solid #000;
					border-radius: 10px;
					box-shadow: 3px 3px 3px red;
				}
		}
		/*large scale devices*/
		@media only screen and (min-width: 768px)and (max-width: 1024px){
			.child{
				width: 25%;
				box-shadow: 0px 8px 8px -8px blue;
			}

		}
	</style>
	<meta charset="utf-8">
</head>

<body bgcolor="pink">
	<div>
	<section class="parent">profile information</section>
	</div>
	<div><section class="child"><img src="126471.svg" alt="heart" width="100"/><h2 align="center">manisha</h2>
			<a href= "maito:manishachitturi5@gmail.com">manishachitturi5@gmail.com</a>
	</section>
		<section class="child"><article class="child2">summaery</article>
		<article class="child2" >i have knowledge in 
			<li>python</li>
				<li>c</li>
				<li>java</li>
				<li>html</li>
				<li>mobile application development</li></article>
	</section></section>
</div>
</body>
</html>
