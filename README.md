<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      background:
      url(
        https://utsavcaterer.in/wp-content/uploads/2019/09/event-management2-1.jpg;
      )
    }

    #loginForm {
        background-color: #899ba7;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    label {
      display: block;
      margin-bottom: 8px;
    }

    input {
      width: 100%;
      padding: 8px;
      margin-bottom: 16px;
      box-sizing: border-box;
    }

    button {
      width: 100%;
      padding: 10px;
      margin-bottom: 8px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    #googleBtn {
      background-color: #4285f4;
      color: #fff;
    }

    #facebookBtn {
      background-color: #3b5998;
      color: #fff;
    }

    #twitterBtn {
      background-color: #1da1f2;
      color: #fff;
    }
  </style>
</head>
<body>

  <div id="loginForm">
    <h2>Login to event management</h2>

    <form>
      <label for="username">Username:</label>
      <input type="text" id="username" name="username" required>

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>

     
      <button id="googleBtn" type="button" onclick="loginWithGoogle()">Login with Google</button>

      
      <button id="facebookBtn" type="button" onclick="loginWithFacebook()">Login with Facebook</button>

      
      <button id="twitterBtn" type="button" onclick="loginWithTwitter()">Login with Twitter</button>

      <button type="submit">Login</button>
    </form>
  </div>

  <script>
    function loginWithGoogle() {
      
      alert("Google login functionality not implemented in this example.");
    }

    function loginWithFacebook() {
      
      alert("Facebook login functionality not implemented in this example.");
    }

    function loginWithTwitter() {
     
      alert("Twitter login functionality not implemented in this example.");
    }
  </script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
	<style>
		body {
			margin: 0;
			padding: 0;
		}
		section {
			width: 100%;
			height: 100vh;
			background:
				url(
					https://www.moretimepa.co.uk/wp-content/uploads/shutterstock_378811030.jpg
				);
			background-size: cover;
		}
		
		section .leftBox {
			width: 50%;
			height: 100%;
			float: left;
			padding: 50px;
			box-sizing: border-box;
		}
		
		section .leftBox .content {
			color: #fff;
			background: rgba(0, 0, 0, 0.5);
			padding: 40px;
			transition: .5s;
		}
		
		section .leftBox .content:hover {
			background: #e91e63;
		}
		
		section .leftBox .content h1 {
			margin: 0;
			padding: 0;
			font-size: 50px;
			text-transform: uppercase;
		}
		
		section .leftBox .content p {
			margin: 10px 0 0;
			padding: 0;
		}
		
		section .events {
			position: relative;
			width: 50%;
			height: 100%;
			background: rgba(0, 0, 0, 0.5);
			float: right;
			box-sizing: border-box;
		}
		
		section .events ul {
			position: absolute;
			top: 50%;
			transform: translateY(-50%);
			margin: 0;
			padding: 40px;
			box-sizing: border-box;
		}
		
		section .events ul li {
			list-style: none;
			background: #fff;
			box-sizing: border-box;
			height: 200px;
			margin: 15px 0;
		}
		
		section .events ul li .time {
			position: relative;
			padding: 20px;
			background: #262626;
			box-sizing: border-box;
			width: 30%;
			height: 100%;
			float: left;
			text-align: center;
			transition: .5s;
		}
		
		section .events ul li:hover .time {
			background: #e91e63;
		}
		
		section .events ul li .time h2 {
			position: absolute;
			margin: 0;
			padding: 0;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
			color: #fff;
			font-size: 60px;
			line-height: 30px;
		}
		
		section .events ul li .time h2 span {
			font-size: 30px;
		}

		
		section .events ul li .details {
			padding: 20px;
			background: #fff;
			box-sizing: border-box;
			width: 70%;
			height: 100%;
			float: left;
		}
		
		section .events ul li .details h3 {
			position: relative;
			margin: 0;
			padding: 0;
			font-size: 22px;
		}
		
		section .events ul li .details p {
			position: relative;
			margin: 10px 0 0;
			padding: 0;
			font-size: 16px;
		}
		
		section .events ul li .details a {
			display: inline-block;
			text-decoration: none;
			padding: 10px 15px;
			border: 1.5px solid #262626;
			margin-top: 8px;
			font-size: 18px;
			transition: .5s;
		}
		
		section .events ul li .details a:hover {
			background: #e91e63;
			color: #fff;
			border-color: #e91e63;
		}
	</style>
</head>
<body>
	<section>
		<div class="leftBox">
			<div class="content">
				<h1>
					Events and shows
				</h1>
				<p>
					The most difficult part of hosting any event is managing it.welcome everyone to event management.therefore,leading 
					companies need to aadd virtual event managementsoftware into frame work. An event plannig software can increase
					the revenue of any virtual event by helping the company easily manage the event.
					Virtual Days helps corporations host the best virtual events by providingthem with state-of the art event management
					services. Our advanced tech and tools aid us in the streamlined flow of work in creating a user-friendly virtual
					event.so our virtual event programming can help the people to easily save theiir time by register in our 
					platform.and our prices are also too low.
				</p>
			</div>
		</div>
		<div class="events">
			<ul>
				<li>
					<div class="time">
						<h2>
							25 <br><span>March</span>
						</h2>
					</div>
					<div class="details">
						<h3>
							Where is the event happening?
						</h3>
						<p>
							EVENT:Eve of Holi<br>
							Guest:Prabhas<br>
							Venue:Lovely Proffesional University,Punjab<br>
							Timing: 7:00am - 11:00am
						</p>
						<a href="#">View Details</a>
					</div>
					<div style="clear: both;"></div>
				</li>
				<li>
					<div class="time">
						<h2>
							27 <br><span>May</span>
						</h2>
					</div>
					<div class="details">
						<h3>
							Where is the event happening?
						</h3>
						<p>
							EVENT:Coke Studio India<br>
							Guest:A.R.Rahaman<br>
							Venue:Hyderabad<br>
							Timing: 6:00pm-10:00pm<br>

						</p>
						<a href="#">View Details</a>
					</div>
					<div style="clear:both;"></div>
				</li>
				<li>
					<div class="time">
						<h2>
							12 <br><span>August</span>
						</h2>
					</div>
					<div class="details">
						<h3>
							Where is the event happening?
						</h3>
						<p>
							EVENT: Tito's club<br>
							Guest:Pooja Hegde<br>
							Venue:Vishakapatnam<br>
							Timing:8:00pm - 12:00am<br>
						</p>
						<a href="#">View Details</a>
					</div>
					<div style="clear:both;"></div>
				</li>
			</ul>
		</div>
	</section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stock Trading Platform - Register</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

   
    body:nth-child(odd) {
      background: linear-gradient(to right, #3498db, #2c3e50);
    }

    
    body:nth-child(even) {
      background:
      url(
        https://images.shiksha.com/mediadata/images/articles/1583747992phpzaxKKK.jpeg
      );
      background-repeat: no-repeat;
      background-size: cover;
    }

    #register-form {
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      width: 300px;
      text-align: center;
    }

    label {
      display: block;
      margin-bottom: 8px;
    }

    input {
      width: 100%;
      padding: 8px;
      margin-bottom: 16px;
      box-sizing: border-box;
    }

    button {
      background-color: #3498db;
      color: #fff;
      padding: 10px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <div id="register-form">
    <h2>Register</h2>
    <form action="#" method="post">
      <label for="username">Username:</label>
      <input type="text" id="username" name="username" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>

      <button type="submit">Register</button>
    </form>
  </div>

</body>
</html>
