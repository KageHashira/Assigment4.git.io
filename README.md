<html>
<head>
    <script>
        function hello() {
            
            var u = document.getElementById("fname");
            alert (" Your Password is " + u.value);
            

        }
        function myFunction(){
            var x = document.getElementById("fname");
            x.value = x.value.toUpperCase();
        }
        function hov()
        {
            var e = document.getElementById('hover');
            e.style = "background-color: rgb(255, 0, 255);height: 30px; width: 100px;"; //e.style.display = 'none';
            
        }
        function hove()
        {
            var e = document.getElementById('hover');
           e.style = "background-color: rgb(0, 4, 255);height: 30px; width: 100px;"; 
        }
</script>
</head>
<body background="C:\Users\arnav\Desktop\photo-1553095066-5014bc7b7f2d.jpeg" style="color: rgb(102, 255, 0); font-size: large; font-family: 'Times New Roman', Times, serif;" >
    
    <h1 style="text-align: center;">Welcome to Mohanlal sukharaya University </h1> <br> <p style="color: rgb(255, 0, 234);">Enter your name: <input type = "text" id = "pname" onkeyup="myFunction()"></p>
    <p style="color: darkgoldenrod;">Enter your Password: <input type = "password" id = "fname" onkeyup="myFunction()">
    <button type = "button" onclick="hello()"> Click to view your entered Password  </button></p>
    <p style="color: gold;">Enter your birth date
    <input type="date" id="datee"> </p>
    <h3 style="color: rgb(129, 247, 174);">Select your course
    <select name = "option">
        <option value = "aa">BCA</option>
        <option value = "bb">BBA</option>
        <option value = "cc">BCOMM</option>
        <option value = "dd">BSC</option>
        <option value = "ee">BTECH</option></select></h3>
    <h3 style="background-color: Red; text-align: center;">Click on Image to view real website</h3>
    <button type = "button"  onclick="location.href = 'https://www.mlsu.ac.in/'"> <img src="D:\One Piece\MLSU.jpg"  alt="Website" height="500px" width="750px">  </button>
    <div id = "hover" onmouseover="hov()" onmouseleave="hove()" 
    style = "background-color: rgb(0, 4, 255);height: 30px; width: 100px;";> <p style="text-align: center; text-anchor: middle; color: rgb(9, 255, 0);"><a href="https://www.mlsu.ac.in/" style="color: black;">Join us!!</a></p></div> <br><br>
    <hr>
    <h2>Follow us For more Info</h2>
    <button type = "button" onclick="location.href = 'https://www.instagram.com/apnamlsu/?hl=en'"> <img src="D:\One Piece\Instagram-Logo-PNG-Image-1.png" alt="Website" height="50px" width="50px">  </button>
    <button type = "button" onclick="location.href = 'https://www.facebook.com/mohanlalsukhadiauniversityudaipur/'"> <img src="D:\One Piece\pngwing.com.png" alt="Website" height="50px" width="50px">  </button>
    <button type = "button" onclick="location.href = 'https://twitter.com/mlsuudaipur?lang=en'"> <img src="D:\One Piece\pngegg.png" height="50px" width="50px">  </button>
   
    
</body>
</html>
