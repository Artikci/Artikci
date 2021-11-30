<html>
    <head>
        <title> Նկարներ </title>
    </head>
    <style>
         *
            {
                padding: 0 ;
                margin: 0 ;
            }
        body
            {
                background-attachment: fixed;  
                font-size: 20px; 
                background: url(3.jpg) ;
                background-size: 23%;
            }
        #container
            {
                width: 700px; 
                height: 1000px; 
                border: 3px solid rgb(0, 0, 0); 
                margin-left: auto; 
                margin-right: auto;
                background-color: rgba(115, 105, 206, 0.432);
                padding: 10px;
            }

        #header
            {
                width: 700px;
                height: 300px;
                outline: 1px solid black;
                background: url(1509456426347035951.png) no-repeat;    
                background-size: 700px 300px;    }
            
        #header h1, h3 {
                            color: rgb(0, 0, 0);
                            background-color: rgba(255, 228, 196, 0.425);
                            text-align: center;
                            padding-right: 5%;
                          margin-bottom: 10px;

            }      
        #content 
            {
                width: 485px;
                height: 500px;
                outline: 1px solid black;
                margin-top: 15px;
                float: left;
                background-color: rgba(148, 207, 241, 0.97);
                padding: 10px;

            }

            #content p img {margin-top: 5px;}
        #content p a {color: black; text-decoration: none;}
        #content input:hover { background-color: cyan; cursor: pointer; }
        #content input {margin-top: 5px;}
        #heading2 {
                margin-top: 10px;
            }
        #sidebar
            {
                width: 185px;
                height: 520px;
                outline: 1px solid black;
                overflow: hidden;
                float: right;
                margin-top: 15px;
                background-color: rgba(109, 201, 201, 0.95);

            }
 
            #sidebar ul li 
            {       color: rgb(0, 0, 0);
                margin-top: 20px;
                border-bottom: 2px solid rgb(0, 0, 0);
                margin-bottom: 30px;
                text-align:center; }
                #sidebar ul 
            { margin-top: 20px;}
        #sidebar ul li a {
                color: rgb(0, 0, 0);
                text-decoration: none;
            }
        #sidebar ul li:hover {background-color: rgba(236, 200, 200, 0.808);
        cursor: pointer;}
        
        #HOME {
            width: 350px;
            height: 150px;
            outline: 2px solid black;
            margin-top: 15px;
           
            float: left;
        }
        #HOME a img {
            background: no-repeat center;
        }
        #classic {
            width: 330px;
            height: 150px;
            outline: 1px solid black;
            overflow: hidden;
                float: right;
                margin-top: 15px;
            background: url(sddefault.jpg) no-repeat center;
            background-size: 340px;

            
            


        }
           
    </style>
   
    <body>
        <div id="container">
            <div id="header">
                <h1>Արթիկ</h1>
                <h3>Համար 1 քաղաքը աշխարհում</h3>



            </div>
            <div id="content">
              <p>
                  <img src="14.jpg" style="width: 100%;">
                  <img src="141.jpg" style="width: 70%; right: 10cm;">
              </p>
              <p>
                <a href="file:///C:/Users/Lenovo/Desktop/Html/Galary1.html"><input type="button" value="1" style="width: 40px; height: 25px; background-color: lime;"></a>
                <a href="file:///C:/Users/Lenovo/Desktop/Html/Galary2.html"><input type="button" value="2" style="width: 40px; height: 25px; background-color: lime;"></a>
                <a href="file:///C:/Users/Lenovo/Desktop/Html/Galary3.html"><input type="button" value="3" style="width: 40px; height: 25px; background-color: lime;"></a>
                <a href="file:///C:/Users/Lenovo/Desktop/Html/Galary4.html"><input type="button" value="4" style="width: 40px; height: 25px; background-color: lime;"></a>
  
         





            </div>

            <div id="sidebar">
                <ul>
                    <li><a href="file:///C:/Users/Lenovo/Desktop/Html/2.html">Արթիկ </a></li>
                    <li><a href="file:///C:/Users/Lenovo/Desktop/Html/story.html">Պատմություն</a></li>
                    <li><a href="file:///C:/Users/Lenovo/Desktop/Html/Galary1.html">Նկարներ</a></li>
                    <li><a href="file:///C:/Users/Lenovo/Desktop/Html/interest.html">Հետաքրքիր<a/></li>
                    <li><a href="file:///C:/Users/Lenovo/Desktop/Html/About_us.html">Մեր մասին<a/></li>




                </ul>




            </div>
            <div id="HOME">
                <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15938.246254730173!2d43.96591589614625!3d40.61958825678006!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x406a0ab54033e5e1%3A0xc9ad82ce72dc95c7!2z0JDRgNGC0LjQuiwg0JDRgNC80LXQvdC40Y8!5e0!3m2!1sru!2sus!4v1638192657214!5m2!1sru!2sus" width="350" height="150" style="border:0;" allowfullscreen="" loading="lazy"></iframe>

            </div>
            <div id="classic">
                

            </div>
        </div>
    </body>
</html>
