# Yoga-Website only Homepage 
<html>
    <head>
            <style>

                    .container{
                        display: flex;
                        flex-direction: column;
                        height:100vh;
                        background-size:cover;
                        background-position: center;
                        background-image:  url("logon.jpg");
                    }
                    
                    ul{
                     
                      list-style-type: none;

                    }
                            ul li{
                                
                                float:right;
                                width: 140px;
                                height: 60px;
                                font-size: 15px;
                                line-height:60px;
                                text-align:center;
                                justify-content: space-evenly;
                            }

                             ul li a{
                            text-decoration: none;
                            color: darkgreen;
                            padding: 5px 20px;
                            border: 1px solid transparent;
                            transition: 0.6s ease;
                            
                        }

                            ul li a:hover{
                                background-color:rgb(9, 7, 116);
                                color:white;

                            }
                                ul li ul li{
                                    display:none;
                                    background-color:rgb(250, 210, 247);
                                    box-shadow: rgb(12, 12, 12) 0 2px 6px 0;
                                    height: 70px;
                                    transition: 1s all;
                                 }
                                 ul li:hover ul li{
                                     display:block;
                                     
                                 }
                      
                            ul li.active a{
                                background-color: rgb(218, 141, 218);
                                color:#fff;

                            } 
                    .logo img{
                        float:left;
                        width:100px;
                        height:auto;
                    }
                    .header{
                        position: absolute;
                        bottom: 85%;
                        right: 92%;
                        transform: translate(-50%-50%);
                    }
                        .header h1{
                            color:#000;
                            font-size: 10px;
                        }
                .content1{
                  
                    height:20px;
                    margin-top: 5px;
                    padding: 20px;
                    
                  
                }
                    .content1 h2{
                        position: absolute;
                        bottom: 55%;
                        right: 80%;
                        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, 'sans-serif';
                    }
                    .content1 p{
                        position: absolute;
                        bottom: 25%;
                        right: 47%;
                    }
                    .button{
                        position: absolute;
                        top: 90%;
                        left:18%;
                        transform: translate(-50%-50%);
                    
                    }
                    .btn{
                        border: 1px solid rgb(109, 13, 109);
                        padding: 20px 100px;
                        color:rgb(109, 13, 109);
                        background-color: rgb(239, 194, 245);
                        transition: 0.6s ease;
                    }
                    .btn:hover{
                                background-color:rgb(9, 7, 116);
                                color:white;

                    }
                   .float{
                        background-color: plum;
                        text-shadow: rgb(12, 12, 12);
                        bottom:26%;
                        position: absolute;
                        width:1500px;
                        behavior:inherit;
                        
                   }
                   
                </style>
    </head>
    <body class="container">
        
    
        <div class="header"> 
            <h1> Heal N Feel Club</h1> 
        </div>
            <div class="main">
                <div class="logo">
                    <img src="css/1Logo.png">
                </div>
            <ul>
            <li class="active"><a href="Case study.html">Home</a></li>

            <li><a href="#">Exercise</a>
                <img class="bullet" src="./bullet_m.gif" alt="bullet" />
                    <ul>
                        <li><a href="cardio.html">Cardio</a></li>
                        <li><a href="flexiblity.html">Flexiblity</a></li>
                        <li><a href="strength.html">Strength</a></li>
                        <li><a href="balance.html">Balance</a></li>
                        <li><a href="co-ordination.html">Coordination</a></li>
                        
                    </ul>
                </li>
            <li><a href="#">Yoga</a>
                <img class="bullet" src="./bullet_m.gif" alt="bullet" />
                <ul>
                    <li><a href="Shirshasana.html">Shirshasana</a></li>
                    <li><a href="Siddhasana.html">Siddhasana </a></li>
                    <li><a href="suryanamaskar.html">Surya Namaskar</a></li>
                    <li><a href="prayanama.html">Pranayama  </a></li>
                    <li><a href="savasana.html">Shavasana</a></li>
                </ul>
            </li>
             
             <li><a href="#">Products</a>
                <img class="bullet" src="./bullet_m.gif" alt="bullet" />
                <ul>
                    <li><a href="protein.html">Protein Powder</a>
                    <li><a href="mask.html">Mask</a></li>
                    <li><a href="hair oil.html">Hair Oils</a></li>
                    <li><a href="herbal flavourings.html">Herbal Flavourings</a></li>
                    <li><a href="Gym Tools.html">Gym Tools</a></li>
                    
                </ul>
            </li>
                
        </ul>
        </div>
    </div>

    <div class="float">

        <marquee><b>Welcome To Heal And Feel Club</b></marquee>

    </div>
   
    <div class="button">
        <a href="#" class="btn"><b>Watch Vedio</b></a>
        <a herf="contact.html" class="btn"><b>Contact Us</b></a>
        <a href="email.html" class="btn"><b>Email</b></a>
    </div>
  
           
    </body>
    </html>
