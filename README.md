# Rocket-Payment
A responsive payment page 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Josefin+Sans:wght@500&display=swap" rel="stylesheet">
    <title>Rocket Payment</title>
</head>
<body>
    
    <div class="main">
        <div class="card easy">
            <div class="cam-1">
                <div class="content">
                <img src="easy.png" alt="easy">
                <h3>Easy</h3>
                <span>Acesse o plano Rocket Easy caso seja um Dev Iniciante.</span>
                <input class="btn easy" type="button" src="#" value="Escolher">
                </div>
            </div> 
        </div>
        <div class="card medium">
            <div class="cam-2">
                <div class="content">
                    <img src="medium.png" alt="medium">
                    <h3>Medium</h3>
                    <span>Acesse o plano Rocket Medium caso seja um Dev Intermediário.</span>
                    <input class="btn medium" type="button" src="#" value="Escolher">
                </div>
            </div> 
        </div>
        <div class="card hard">
            <div class="cam-3">
                <div class="content">
                    <img src="hard.png" alt="hard">
                    <h3>Expert</h3>
                    <span>Acesse o plano Rocket Expert caso seja um Dev Expert.</span>
                    <input class="btn hard" type="button" src="#" value="Escolher">
                </div>
            </div> 
        </div>
    </div>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    font-family: 'Bebas Neue', cursive;
}

body {
    background-color: #16151b;
    color: whitesmoke;
    font-size: 18px;
}

.main {
    display: flex;
    justify-content: space-around;
    align-items: center;
    min-width: 350px;
    flex-wrap: wrap;
    
}

img {
    width: 180px;
    height: 180px;
}

.content{  
  width: 260px;
  height: 370px;
  display: flex;
  flex-direction: column;  
  align-items: center;
  background-color: #25242e;
  padding: 5px;
  border-radius: 3px;
  margin-top: 10px;
  margin-bottom: 50px;
}

.btn.easy {
    border-radius: 50px;
    padding: 7px 20px;
    background: linear-gradient(to right, #407bff, #0033a6);
    border: none;
    color: #fff;
    font-size: 18px;
    
}

.btn.medium {
    border-radius: 50px;
    padding: 7px 20px;
    background: linear-gradient(to right, #ffc100, #aa8100);
    border: none;
    color: #fff;
    font-size: 18px;
    
}

.btn.hard {
    border-radius: 50px;
    padding: 7px 20px;
    background: linear-gradient(to right, #ba68c8, #65286f);
    border: none;
    color: #fff;
    font-size: 18px;
    
}

span {
    flex-wrap: wrap;
    max-width: 150px;
    margin: 12px;
}

.cam-1 {
    margin-left: 0px;
    box-shadow: 20px 20px 50px -30px #407bff;
}

.cam-2{
    box-shadow: 20px 20px 50px -30px #ffc100;
}

.cam-3 {
    box-shadow: 20px 20px 50px -30px #ba68c8;
}
