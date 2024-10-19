<!DOCTYPE html>
<html lang="en">
<head>
    <title>MIA-Market Interact Association</title>
    <link rel="stylesheet" type="text/css" href="CSS/ADOOHHH.css">
    <link rel="icon" type="image/x-icon" href="IMG/MIA.jpg">
</head>
<body>
    <header>
        <h1><img src="IMG/MIA.jpg" width="50px" height="50px" style="float: left; margin-left: 3%;">Market Interact Association</h1>
    </header>

    <nav>
        <ul>
            <li><a href="Perusahaan MIA.html">Home</a></li>
            <li><a href="list.html">List</a></li>
            <li><a href="top brand.html">Top Brand</a></li>
            <li><a href="Contact Us.html">Contact</a></li>
            <li><a href="About.html">About</a></li>
        </ul>
    </nav>

    <main class="main-1">
        <section>
            <article>
                <center><figure><img class="SlideShow" src="IMG/Model.jpg" width="100%" height="800px">
                <img class="SlideShow" src="IMG/Model 2.jpg"  width="100%" height="800px">
                <img class="SlideShow" src="IMG/Orang 3.jpeg"  width="100%" height="800px">
                <img class="SlideShow" src="IMG/Adidas.jpg"  width="100%" height="800px">
                <img class="SlideShow" src="IMG/adidas shirt.jpg"  width="100%" height="800px">
                <button style="float: left;" onclick="plusDivs(-1)">&#10094;</button>
                <button style="float: right;" onclick="plusDivs(1)">&#10095;</button></center>
                </figure> 

                <script>
                    var slideIndex = 1;
                    showDivs(slideIndex);
                    
                    function plusDivs(n) {
                      showDivs(slideIndex += n);
                    }
                    
                    function showDivs(n) {
                      var i;
                      var x = document.getElementsByClassName("SlideShow");
                      if (n > x.length) {slideIndex = 1}
                      if (n < 1) {slideIndex = x.length}
                      for (i = 0; i < x.length; i++) {
                        x[i].style.display = "none";  
                      }
                      x[slideIndex-1].style.display = "block";  
                    }
                    </script>
                <p>BEST SHIRT AND SHOES IN HISTORY</p>
                <p style="font-size: 30px; padding-top: 0;">Make your days brighter and wonderful</p>
                <p style="font-size: 20px;">Sport, Holiday, Work</p>
                <p>Whatever you want</p>
                <figure><a href="list.html"><img class="img-a" src="IMG/adidas biru.jpg" width="300px" height="300px" style="float: left; margin-left: 20%;"></a><p style="position: absolute;padding-top: 300px;padding-left: 360px;">Shoe</p>
                <a href="list.html"><img class="img-a" src="IMG/Baju item.png" width="300px" height="300px" style="float: left; margin-left: 10%;"></a><p style="position: absolute;padding-top: 300px;padding-left: 780px;">Shirt</p></figure>
               
            </article>
        </section>
    </main> 

    <footer>
        <p>&copy; This is belong to Muhammad Iqbal Abdillah</p>
    </footer>
    
</body>
</html>
