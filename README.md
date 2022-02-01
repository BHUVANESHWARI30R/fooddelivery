# fooddelivery

//html//

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
    <nav>
        <div class="nav-icon">
          <div></div>
        </div>
      </nav>
     
      </header>
      <br>
    <section>
        <fieldset>
            <legend class="image"><img src="pizza.jpeg" alt="Avatar" class="avatar"></legend>
        <div>
        <h2>Pizza</h2><h5>25 items</h5><br>
    </div>

        <legend class="avatar1">></legend>

        <br>
     </fieldset>
     <br>
        <fieldset>
            <legend class="image"><img src="salads.jpeg" alt="Avatar" class="avatar"></legend>
        <div>
            <h2>Salads</h2><h5>30 items</h5>
        </div>

        <legend class="avatar1">></legend>

        <br>
     </fieldset>
     <br>
        <fieldset>
            <legend class="image"><img src="dessert.jpeg" alt="Avatar" class="avatar"></legend>
        <div>
            <h2>Desserts</h2><h5>30 items</h5>
        </div>
       
        <legend class="avatar1">></legend>
        
        <br>
    </fieldset>
    <br>
        <fieldset>
            <legend class="image"><img src="pasta.jpeg" alt="Avatar" class="avatar"></legend>
        <div>
            <h2>Pasta</h2><h5>44 items</h5>
        </div>

        <legend class="avatar1">></legend>

        <br>
    </fieldset>
    <br>
        <fieldset>
            <legend class="image"><img src="beverages.jpeg" alt="Avatar" class="avatar"></legend>
        <div>
            <h2>Beverages</h2><h5>30 items</h5>
        </div>

        <legend class="avatar1">></legend>

        <br>
        </fieldset>
       
    </section>
    
   
   
</body>
</html>







//css//


nav{
 
  padding: 20px;
 
}
nav:hover{
  box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
}
.nav-icon {
    margin: 0;
    width: 30px;
    cursor: pointer;
}

.nav-icon:after,
.nav-icon:before,
.nav-icon div {
    background-color: rgb(255, 255, 255);
    border-radius: 3px;
    content: "";
    display: block;
    height: 2px;
    margin: 7px 0;
    transition: all 0.2s ease-in-out;
}


.nav-icon:hover {
  box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
}
section{
  padding-left: 100px;
}
fieldset {
    width: 180px;
    height:auto;
    padding-top: 1px;
    padding-left: 40px;
    padding-right: 40px;    
    padding-bottom: 5px;
    margin: 0;
    border-radius: 10%;  
    box-shadow: 5px 5px 3px rgb(235, 231, 231);
    border: 2px solid rgb(241, 206, 209);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;  
    background-color: aliceblue;    
  }
  h2{
    color: rgb(1, 1, 39);
  }
fieldset:hover{
    box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
  }
.avatar {
    vertical-align:baseline;
    width: 80px;
    height: 80px;
    border-radius: 0%;  
    box-shadow: 3px 3px 1px rgb(212, 198, 198);
    border: 2px solid rgb(238, 210, 210);

  }
.avatar:hover {
    box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
  }
  .avatar1 {
    vertical-align:baseline;
    width: 40px;
    height: 40px;
    border-radius: 20%;  
    box-shadow: 3px 3px 1px rgb(226, 226, 226);
    border: 2px solid rgb(253, 223, 223);
    text-align: center;
    border-radius: 80%;  
    padding-top: 5%;
    padding-left: 5%;
    padding-right: 5%;
    padding-bottom: 5%;
    text-size-adjust:inherit;
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='7.41' height='12' viewBox='0 0 7.41 12'%3E%3Cpath d='M10,6,8.59,7.41,13.17,12,8.59,16.59,10,18l6-6Z' transform='translate(-8.59 -6)' fill='%23fff'/%3E%3C/svg%3E");
  }
.avatar1:hover {
    box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
  }
h5{
  color: #a0a0a0; 
  
}
body{
  background: linear-gradient(to left, #ffffff 50%, #ff0000 50%);
  background-size: 100% auto;
  width: 100%;
}
