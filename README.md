# Navigtion Bar

<!DOCTYPE html>
<html lang="en">
<head>
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
 <meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <link rel="stylesheet" href="Nav.css">
 <title>Nav-Bar</title>
</head>
<body>
     <div class="navbar">
         <a href="#home"> <i class="fa fa-home"></i> <span class="tab1"></span> Home </a>
         <a href="#home"> <i class="fa fa-code"></i> <span class="tab1"></span> Code </a>
         <a href="#home"> <i class="fa fa-user"></i> <span class="tab1"></span> Profile </a>
         <a href="#home"> <i class="fa fa-youtube-play"></i> <span class="tab1"></span> My Channel </a>
         <div class="dropdown">
            <button class="dropbtn">More
                 <i class="fa fa-caret-down"></i>
            </button>
            <div class="dropdown-content">
              <a href="#L1"> <i class="fa fa-link"></i> Link 1 </a>
              <a href="#L1"> <i class="fa fa-link"></i> Link 2 </a>
              <a href="#L1"> <i class="fa fa-link"></i> Link 3 </a>
            </div>
         </div>
     </div>
</body>
</html>




#Css👇🏼👇🏼




body{
 background: #E15D44;
}

.navbar {
 border-radius: 50px;
 overflow: hidden;
 background-color: #333;
 font-family: Arial;
 text-align:center;
 margin-left: 50px;
 margin-right: 50px;
/* margin-top : 300px; */
}

.navbar a {
 border-radius: 50px;
 float: left;
 font-weight: bold;
 font-size: 16px;
 color: white;
 text-align: center;
 padding: 14px 20px;
 text-decoration: none;
}

.dropdown {
 float: left;
 overflow: hidden;
}

.dropdown .dropbtn {
 font-size: 16px;
 border: none;
 outline: none;
 color: white;
 padding: 14px 16px;
 background-color: inherit;
 font-family: inherit; 
 margin: 0; 
}

.navbar a:hover, .dropdown:hover .dropbtn {
 background-color: rgb(0, 0, 0);
}

.dropdown-content {
 display: none;
 position: absolute;
 background-color: #292626;
 min-width: 160px;
 box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
 z-index: 1;
}

.dropdown-content a {
 border-radius: 5px;
 float: none;
 color: white;
 background-color: rgb(0, 0, 0);
 padding: 12px 16px;
 text-decoration: none;
 display: block;
 text-align: left;
}

.dropdown-content a:hover {
 background-color: #333;
}

.dropdown:hover .dropdown-content {
 display: block;
 border-radius: 150px;
}

.tab1{
 padding:2px;
}

