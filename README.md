# PROJECT
Food
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
<title>]food</title>
<style>
body {
margin: 0px;
padding: 0px;
box-sizing: border-box;
}

.main {
width: 100%;
}

nav {
width: 100%;
background-color: #1A2421;
height: 60px;
line-height: 70px;
display: flex;
justify-content: space-between;
}
.logo a{
font-size: 30px;
color: salmon;
font-family: cursive;
font-weight: bold;
}
a{
text-decoration: none;
color: mistyrose;
font-family: copperplate;
font-size: 17px;
transition: 0.5s all ease;
}
ul{
margin: 0px;
}
ul li{
float: left;
padding: 0px 10px;
list-style: none;
}
ul li a:hover {
color: salmon;
}

.header{
background-image: url("https://jooinn.com/images/wood-background-99.jpg");
background-position: center;
background-size: cover;
background-repeat: no repeat;
height: 100vh;
}

.food-cards{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    padding: 2em;
}

.food-card{
    flex: 0 1 20%;
    padding: 1em;
    box-shadow: 2px 2px 50px rgba(0,0,0,0.3);
    margin-bottom: 2em;
    border-radius: .5em;
    transition: .5s;
}

.food-card img{
    width: 100%;
    height: 50%;
}

.food-card:hover{
    transform: scale(1.05);
}

.content{
position: absolute;
top: 90%;
left: 50%;
transform: translate(-50%, -50%);
color: mistyrose;
text-align: center;
font-weight: bold;
}

.content p {
padding: 0px 12px;
font-size: 40px;
}

button {
background: none;
border: 5px solid #fff;
font-size: 25px;
color: #fff;
padding: 4px 12px;
border-radius: 20px;
transition: 0.5s all ease;
font-weight: bold;
}

button:hover {
background: black;
color: red;
}

.overlay {
  position: fixed;
  display: none; 
  width: 100%; 
  height: 100%; 
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0,0,0,0.5); 
  z-index: 2; 
  cursor: pointer; 
}

footer{
    background: #1A2421;
    text-align: center;
    padding: 1em;
font-style: italic;
font-weight: bold;
color: mistyrose;
font-family: monospace;
bottom: 0;
left: 0;
right: 0;
}
</style>
</head>
<body>
<div class="main">
 <div class="wrapper">
  <div class="header">
    <nav>
     <div class="logo">
       <a href="">BOKE BITES</a>
     </div>
     <ul>
    <li><a href="C:\Users\To\Desktop\PROJECT\home.HTML">HOME</a></li>
      <li><a href="C:\Users\To\Desktop\PROJECT\about.html">ABOUT</a></li>
      <li><a href="C:\Users\To\Desktop\PROJECT\blog.html">BLOG</a></li>
      <li><a href="C:\Users\To\Desktop\PROJECT\services.html">SERVICES</a></li>
      <li><a href="C:\Users\To\Desktop\PROJECT\contact.html">CONTACT</a></li>
     </ul>
    </nav>
<main>
    <section class="food-cards">
        <div class="food-card">
            <img src="https://www.liquor.com/thmb/uYuGa53iW3PZ9JUF9GyXSZ8-GKE=/960x0/filters:no_upscale():max_bytes(150000):strip_icc()/__opt__aboutcom__coeus__resources__content_migration__liquor__2019__06__10152522__Wormhole-Warrior-720x720-recipe-c121b4b99eaa4396a5d7f7dec15028fe.jpg">
        </div>
        <div class="food-card">
            <img src="https://i.pinimg.com/564x/3b/12/cf/3b12cf06d035b7d03d507d7c748c68f3.jpg">
        </div>
        <div class="food-card">
            <img src="https://i.pinimg.com/564x/c9/84/8a/c9848a54e12067f7fe99278af04546b3.jpg">
        </div>
        <div class="food-card">
            <img src="https://i.pinimg.com/564x/0a/91/41/0a914133013068d043560ae2b892046b.jpg">
        </div>
    </section>
</main>
   <div id="overlay"></div>
   <div class="content"
      <p>Meet, Greet and Enjoy true African taste.</p>
      <button>ORDER HERE</button>
   </div>
   </div>
</div>
</div>
<footer>
    Thank you for visiting BOKE BITES, where taste is passion.
</footer>
</body>
</html>
