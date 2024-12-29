# Ex.07 Restaurant Website
# Date:21/10/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MERCATO MISSION</title>
    <link rel="icon" href="ima 4.png">  
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url(html.png);

        }
        .menu {
            display: flex;
            flex-direction: column;
            width: 200px;
            margin: 0 auto;
            padding: 20px;
        }
        .menu-item {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            margin: 5px;
            text-align: center;
            cursor: pointer;
        }
        .menu-item:hover {
            background-color: #45a049;  
        }
        .content {
            display: none;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body><center>
    <img src="ima 4.png"style="height: 150px;width: 150px;">
    <h1 style="background-color:burlywood;">MERCATO<BR>MISSION</h1><hr>
   
    </center>

    <h1></h1>

    <div class="menu">
        <div class="menu-item" onclick="showPage('page1')">Menu </div>
        <div class="menu-item" onclick="showPage('page2')">Administration</div>
        <div class="menu-item" onclick="showPage('page3')">contact</div>
    </div>
    <center>
        <br><br><br><br><br><br><br><br><br><br>
    <h1 style="color: rgb(238, 239, 239);">Designed and Developed by Priyadharshini j @ 2024</h1>
    </center>

    <div id="page1" class="content">
        <h2>Page 1</h2>
        <p><h2> MENU.</h2><BR><hr>
        
                <tr>
            <h1 style="background-color: aqua;">PIZZA MARGHERITA</h1>
        <IMg src="pizza.jpg"style="height: 250px;px;width: 250px;px;">
       <h2 style="background-color: rgb(245, 210, 106);"> A classic pizza with tomato,mozzarella,and basil.<br>$120</h2>
        
           <h1 style="background-color: aqua;">LASAGNA</h1>
        <img src="lasa.jpg"style="height: 250px;px;width: 250px;px;">
        <h2 style="background-color:rgb(245, 210, 106) ;">Layers of pasta,meat sauce,and cheese, baked in the oven<br>$150</h2>

        <h1 style="background-color: aqua;">SPAGHETTI CARBONARA</h1>
           <img src="sapg.jpg"style="height: 250px;px;width: 250px;px;">
           <H2 style="background-color: rgb(245, 210, 106);">Pasta with eggs,pancetta,and pecorino romano cheese<br>$180</H2><hr>

           <h1 style="background-color: aqua;">RISOTTO ALLA MILANESE</h1>
             <img src="risotta.jpg"style="height: 250px;px;width: 250px;px;">
             <h2 style="background-color: rgb(245, 210, 106);">Creamy risoota flavored with saffrom<br>$200</h2><hr>

             <h1 style="background-color: aqua;">TIMAMISU</h1>
             <img src="tira.jpg"style="height: 250px;px;width: 250px;px;">
             <h2 style="background-color: rgb(245, 210, 106);">a coffee-flavored dessert made with mascarpone cheese and ladyfingers<br>$240</h2><hr>

              <h1 style="background-color: aqua;">BRUSCHETTA</h1>
              <img src="brus.jpg"style="height: 250px;px;width: 250px;px;">
              <h2 style="background-color: rgb(245, 210, 106);">grilled bread topped with garlic, tomatoes,and olive oil<br>$220</h2><hr>

              <h1 style="background-color: aqua;">FOCACCIA</h1>
              <img src="foccasia.jpg"style="height: 250px;px;width: 250px;px;">
              <h2 style="background-color: rgb(245, 210, 106);">A flatbread ,often topped with herbs,olive oil,and sea salt<br>$280</h2><hr>

              <h1 style="background-color: aqua;">RAVIOLI</h1>
              <img src="ravioli.jpg"style="height: 250px;px;width: 250px;px;">
              <h2 style="background-color: rgb(245, 210, 106);">pasta pockets filled with cheese,meat,or vegetables<br>$300</h2><hr>

              <h1 style="background-color: aqua;">OSSO BUCO</h1>
              <img src="osso.jpg"style="height: 250px;px;width: 250px;px;">
              <h2 style="background-color: rgb(245, 210, 106);">braised veal shanks in a rich sauce<br>$350</h2><hr>

              <h1 style="background-color: aqua;">GELATO</h1>
              <img src="gelato.jpg"style="height: 250px;px;width: 250px;px;">
              <h2 style="background-color: rgb(245, 210, 106);">italian-style ice cream,known for its creamy texture<br>$380</h2><hr>

              <h1 style="background-color: aqua;">PIATTO</h1>
              <img src="pizza.jpg"style="height: 250px;px;width: 250px;px;">
              <h2 style="background-color: rgb(245, 210, 106);">In Italian cuisine, a piatto unico is a single-course meal that combines proteins and starches. <br>$400</h2><hr>

              <h1 style="background-color:aqua;">PUTANESCA PASTA</h1>
              <img src="putanesca pasta.png"style="height: 250px;px;width: 250px;px;">
              <h2 style="background-color: rgb(245, 210, 106);">This quick southern Italian sauce is a pungent, briny collaboration of anchovies, olives, and capers within a chunky tomato base.<br>$450</h2><hr>

             </p>
            </tr>
            </table>
        <button onclick="goBack()">Back to Menu</button>
    </div>

    <div id="page2" class="content">
        <h2>Page 2 </h2>
        <p><h1 style="background-color: rgb(43, 186, 177);">ADMINISTRATION</h1><br><hr>
           <h2 style="background-color: rgb(237, 235, 186);"> MERCATO mission Restaurant  is a restaurant chain that operates primarily in the Indian state of Tamil Nadu.<br>
             The first outlet was opened in 1957 at Dindigul.<br>
              Since then, it operates with over 101 outlets globally with 92 outlets in India, and 9 outlets overseas.<br>
               The Thalappakatti restaurants focus on italian menu's as the core product.<br><br>
               <img src="rest2.avif" width="300px" height="300px">  <img src="rest.jpeg" width="300px" height="300px">
               <img src="rest4.avif" width="300px" height="300px">
              <hr> Right from the beginning, he always emphasized<br> on taste and ensured that the Biriyani made at<br>
                his hotel was both delicious and unique. This<br> was achieved and still is by meticulous selection
                 <br>of ingredients prepared from quality masala products.<br> Biriyani was prepared using superior quality Seeraga samba rice,<br>
                known as Parakkum sittu and meat obtained from top-class breeds of <br>
                cattle particularly found in the famous cattle-markets of Kannivadi and Paramathi.</h2>
        </p>
        <button onclick="goBack()">Back to Menu</button>
    </div>

    <div id="page3" class="content">
        <h2>Page 3 </h2>
        <p><h2 style="background-color: rgb(43, 186, 177);">CONTACT</h2><BR><hr>
            <img src="rest3.avif" height="200px" width="150">
            
        <h2 style="background-color: azure;"> phone no: 8838512605 | email -"mercto mission@gmail.com"|<br>
            mercto mission hotels Pvt Ltd.,<br>
        no,25/30,Fourth floor,<br>
        ramky house , chennai 604206
        </h2>
        </p>
        <button onclick="goBack()">Back to Menu</button>
    </div>

    <script>
        function showPage(pageId) {
            // Hide all content sections
            var contents = document.querySelectorAll('.content');
            contents.forEach(function(content) {
                content.style.display = 'none';
            });

            // Show the selected content
            document.getElementById(pageId).style.display = 'block';

            // Hide the menu
            document.querySelector('.menu').style.display = 'none';
        }

        function goBack() {
            // Show the menu
            document.querySelector('.menu').style.display = 'flex';

            // Hide all content sections
            var contents = document.querySelectorAll('.content');
            contents.forEach(function(content) {
                content.style.display = 'none';
            });
        }
    </script>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (47).png>)
![alt text](<Screenshot (48).png>)
![alt text](<Screenshot (49).png>)
![alt text](<Screenshot (50).png>)
![alt text](<Screenshot (51).png>)
![alt text](<Screenshot (52).png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
