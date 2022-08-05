
<!DOCTYPE html>
<html lang="en">
<head>
				<meta charset="UTF-8">
				<meta name="viewport" content="width=device-width, initial-scale=1.0">
				<title>Facebook</title>
				<li  href="http://fontawesome.io/icons/">
				<link rel="stylesheet" href="style.css">
				<script src="index.js"></script>
		</head>
		<body>
				<section id="first">
								<div id="head">
												<b>facebook<a class ="search" href="www.google.com"><img  src="search.jpg" alt="search"></a><a class="message" href="www.youtube.com"><img src="message.png" alt="message"></a></b>
												<!--  <button class="search"><img src="search.jpg" alt="search"></button> -->
								</div>
								<nav id="down">
										<a href="home.html">Home</a>	
										<a href="friends.html">Friends</a>	
										<a href="video.html">Videos</a>
										<a href="profile.html">Profile</a>
										<a href="notification.html">Notifications</a>
										<a href="menu.html">Menu</a>
												
								</nav>
								<hr>
				</section>
				<section id="second">
								<div>
							<a href="profile.html"><img class="profile" id="output"alt="bijay"></a>
							<input type="span" id="post" placeholder="Whats on your mind?">
							<br>
							</div>
							<br>
							<br>
				</section>
				
				<p>		
				<!--  <button style="display:block;width:120px; height:30px;" onclick="document.getElementsByTagName("input").click()">Your text here</button> -->
																
			
<video controls>
  Your browser does not support the video tag.
</video>
	<input type='file'  id='videoUpload' />
<script>
document.getElementById("videoUpload")
.onchange = function(event) {
  let file = event.target.files[0];
  let blobURL = URL.createObjectURL(file);
  document.querySelector("video").src = blobURL;
}
</script>
				</p>
				<i class="fa fa-heart" aria-hidden="true" id="heart" onClick="like()" bgcolor="whute"><sectio</section>7</i>
				<script>
								var likeCount = 10;
								 function like(){ 
								 likeCount++;
								  }
				</script>
				<button onclick="loadFile()"></button>
				
			
</body>
</html>
