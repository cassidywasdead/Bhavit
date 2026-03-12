# Bhavit
Bhavit 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title> Next pornstar bhavit?</title></title>

<style>
body{
font-family: Arial, sans-serif;
text-align:center;
background:#ffe6f0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
}

h1{
font-size:40px;
}

button{
padding:12px 25px;
font-size:20px;
margin:10px;
cursor:pointer;
border:none;
border-radius:10px;
}

#yes{
background:green;
color:white;
}

#no{
background:red;
color:white;
position:absolute;
}

#result{
display:none;
font-size:35px;
color:purple;
}
</style>
</head>

<body>

<h1>Bhavit weds dhanu?? ❤️</h1>

<button id="yes">Yes</button>
<button id="no">No</button>

<div id="result">
🎉 Congratulations! You chose YES! 🎉
</div>

<script>

const noBtn = document.getElementById("no");

noBtn.addEventListener("mouseover", function(){

let x = Math.random()*window.innerWidth*0.8;
let y = Math.random()*window.innerHeight*0.8;

noBtn.style.left = x + "px";
noBtn.style.top = y + "px";

});

document.getElementById("yes").onclick = function(){
document.querySelector("h1").style.display="none";
document.getElementById("yes").style.display="none";
document.getElementById("no").style.display="none";
document.getElementById("result").style.display="block";
}

</script>

</body>
</html>
