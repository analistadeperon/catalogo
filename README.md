# catalogo

<div id="app"></div>

         Data

<input type="date" required="required" maxlength="10" name="date" pattern="[0-9]{2}\/[0-9]{2}\/[0-9]{4}$" min="2012-01-01" max="2014-02-18" />
Hora

<input type="time" required="required" maxlength="8" name="hour" pattern="[0-9]{2}:[0-9]{2} [0-9]{2}$" />
Campos genéricos de texto

<input type="text" required="required" name="name" />
Telefone

<input type="tel" required="required" maxlength="15" name="phone" pattern="\([0-9]{2}\) [0-9]{4,6}-[0-9]{3,4}$" />

Email

<input type="email" required="required" class="input-text" name="email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$" />
Modelo projeto

<input type="tel" required="required" maxlength="15" name="valor" pattern="([0-9]{1,3}\.)?[0-9]{1,3},[0-9]{2}$" />

<div>
    <label for="username">Username:</label>
    <input type="text" id="username" name="username">
</div>
<div>
    <label for="pass">Password (8 characters minimum):</label>
    <input type="password" id="pass" name="password"
           minlength="8" required>
</div>

<input type="submit" value="Sign in">

<input type="file" name="file" accept="image/*" required="required" />
<html>
<head>
<title>HTML Video Tag Example</title>
</head>
<body>
<br>
<video id="custom_video_play" width="400" controls="controls">>
<source src="Yes Bank Advertisment.mp4" type="video/mp4"><source src="mov_bbb.flv" type="video/flv"> Browser Not Supporting
</video>
</div>
<script>
var myVideo=document.getElementById("custom_video_play");
function makeBig()
{
myVideo.width=650;
}
function makeSmall()
{
myVideo.width=350;
}

function makeNormal()
{
myVideo.width=450;
}
</script>
<div style="text-align:left">
<button onclick="makeBig()">Adjust: Large Screen</button>
<button onclick="makeSmall()">Adjust: Small Screen</button>
<button onclick="makeNormal()">Adjust: Normal Screen</button>
<p></p>
tdBotoes.html("<img src='https://www.reneelab.biz/wp-content/uploads/sites/9/2016/04/Como-editar-v%C3%ADdeo.png' class='btnSalvar'/>");


