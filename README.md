*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{

background:#fafafa;

display:flex;

justify-content:center;

align-items:center;

height:100vh;

}

.container{

width:1100px;

height:650px;

background:white;

display:flex;

border-radius:20px;

overflow:hidden;

box-shadow:0 0 25px rgba(0,0,0,.15);

}

.left{

flex:1;

background:linear-gradient(135deg,#6C63FF,#00C2FF);

color:white;

padding:60px;

display:flex;

flex-direction:column;

justify-content:center;

}

.left h1{

font-size:40px;

margin-bottom:20px;

}

.left p{

font-size:18px;

margin-bottom:30px;

line-height:30px;

}

.left img{

width:100%;

border-radius:20px;

}

.right{

flex:1;

display:flex;

justify-content:center;

align-items:center;

background:white;

}

.login-box{

width:380px;

}

.login-box h2{

text-align:center;

margin-bottom:30px;

}

input{

width:100%;

padding:14px;

margin-bottom:15px;

border:1px solid #ccc;

border-radius:10px;

font-size:16px;

}

button{

width:100%;

padding:14px;

border:none;

border-radius:10px;

font-size:16px;

cursor:pointer;

background:#6C63FF;

color:white;

margin-bottom:15px;

}

.google{

background:#DB4437;

}

.facebook{

background:#1877F2;

}

.or{

text-align:center;

margin:15px;

font-weight:bold;

color:gray;

}

p{

text-align:center;

}

a{

text-decoration:none;

color:#6C63FF;

font-weight:bold;

}

button:hover{

opacity:.9;

}
