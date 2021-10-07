# HTML
Trying my hands on HTML



<!DOCTYPE html>
 
<html>
 
<head>
    <title>NAmikaze Minato</title>
     <style>
        * {
            margin: 0;
            padding: 0;
        }
 
        .navbar {
            display: flex;
            align-items: center;
            justify-content: center;
            position: sticky;
            top: 0;
            cursor: pointer;
        }
         .background {
            background: black;
            background-blend-mode: darken;
            background-size: cover;
        }
 
        .nav-list {
            width: 70%;
            display: flex;
            align-items: center;
        }

         .nav-list li {
            list-style: none;
            padding: 26px 30px;
        }
 
        .nav-list li a {
            text-decoration: none;
            color: white;
        }
 
        .nav-list li a:hover {
            color: grey;
        }
 
        .rightnav {
            width: 30%;
            text-align: right;
        }

 
        .firstsection {
            background-color: Yellow;
            height: 400px;
        }
 
        .secondsection {
            background-color: blue;
            height: 400px;
        }
 
        .box-main {
            display: flex;
            justify-content: center;
            align-items: center;
            color: black;
            max-width: 80%;
            margin: auto;
            height: 80%;
        }
 
        .firsthalf {
            width: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
 
        .secondhalf {
            width: 30%;
        }
 
        .secondhalf img {
            width: 70%;
            border: 4px solid white;
            border-radius: 150px;
            display: block;
            margin: auto;
        }
 
        .text-big {
            font-family: 'Piazzolla', serif;
            font-weight: bold;
            font-size: 35px;
        }
 
        .text-small {
            font-size: 18px;
        }
 
        .btn {
            padding: 8px 20px;
            margin: 7px 0;
            border: 2px solid white;
            border-radius: 8px;
            background: none;
            color: white;
            cursor: pointer;
        }
 
        .btn-sm {
            padding: 6px 10px;
            vertical-align: middle;
        }
 
        .section {
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            max-width: 90%;
            margin: auto;
        }
 
        .section-Left {
            flex-direction: row-reverse;
        }
 
        .paras {
            padding: 0px 65px;
        }
 
        .thumbnail img {
            width: 250px;
            border: 2px solid black;
            border-radius: 26px;
            margin-top: 19px;
        }
 
        .center {
            text-align: center;
        }
 
        
    </style>
</head>
 
<body>
    <nav class="navbar background">
        <ul class="nav-list">
         
             <li><a href="#web">Minato</a></li>
            <li><a href="#program">Yellow Flash</a></li>
            <li><a href="#course">Hokage</a></li>
        </ul>
 
        <div class="rightNav">
            
        </div>
    </nav>
<section class="firstsection">
        <div class="box-main">
            <div class="firstHalf">
                <h1 class="text-big" id="Minato">
                    Minato
                </h1>
                 
                <p class="text-small">
                    Minato Namikaze was the Fourth Hokage of Konohagakure. 						He was renowned all over the world as Konoha's Yellow 						Flash ( Konoha no Kiiroi Senkō, English TV: Yellow Flash 					 of the Leaf). He died during the Nine-Tailed Demon Fox's 					  Attack, sacrificing his life to seal a part of the Nine-					  Tails into his newborn son, Naruto Uzumaki.
                </p>
 
            </div>
        </div>
    </section>
 
    <section class="secondsection">
        <div class="box-main">
            <div class="secondHalf">
                <h1 class="text-big" id="Yellow Flash">
                    The Yellow Flash
                </h1>
                <p class="text-small">
                    Minato and Kushina were a couple from the time that he rescued her, and with his love, Kushina was able to keep the Nine-Tails sealed within her at bay. They eventually married. From observing a Tailed Beast Ball, Minato began a three-year process of creating the Rasengan, the height of shape transformation. He would spend the rest of his life trying to combine it with his own nature.
                </p> 
 
            </div>
        </div>
    </section>
 
    <section class="section">
        <div class="paras">
            <h1 class="sectionTag text-big">Hokage</h1>
 
            <p class="sectionSubTag text-small">
                For his performance during the War, Minato was chosen over Orochimaru to become Fourth Hokage.He taught the Flying Thunder God Technique to the Hokage Guard Platoon to better aid them in their duties of serving the Hokage at any given time.In the anime, he also tried to help Kakashi, now an Anbu, emerge from the darkness he'd fallen into after Obito and Rin's deaths. 
            </p>
 
 
        </div>
 
        <div class="thumbnail">
            <img src="https://c4.wallpaperflare.com/wallpaper/334/432/15/anime-naruto-hokage-naruto-minato-namikaze-wallpaper-preview.jpg" alt="Minato">
        </div>
    </section>
 
   
</body>
 
</html>
