[Yesterday 9:37 PM] Vaishnavi Rastogi

<div class="w3-content w3-section bbClass" style="width:800px; height:500px" >

            <div class="mySlides" style="width:100%; height:80%; position: relative;">

                <img src="Images/images.jpg" style="width:100%; height:100%" />

                <div class="overlay">

                    <h4><b>Sattva Park Cubix</b></h4>

                    <p>DEvanahali, Benguular</p>

                    <h5><b>Rs. 43.63 L</b></h5>

                    <button class="btn btn-success">check Out</button>

                </div>

 

            </div>

 

            <div class="mySlides" style="width:100%; height:80%; position: relative;">

                <img src="Images/images1.jpg" style="width:100%; height:100%" />

                <div class="overlay">

                    <h4><b>Sattva Park Cubix</b></h4>

                    <p>DEvanahali, Benguular</p>

                    <h5><b>Rs. 43.63 L</b></h5>

                    <button class="btn btn-success">check Out</button>

                </div>

 

            </div>

 

            <div class="mySlides" style="width:100%; height:80%; position: relative;">

                <img src="Images/images2.jpg" style="width:100%; height:100%" />

                <div class="overlay">

                    <h4><b>Sattva Park Cubix</b></h4>

                    <p>DEvanahali, Benguular</p>

                    <h5><b>Rs. 43.63 L</b></h5>

                    <button class="btn btn-success">check Out</button>

                </div>

 

            </div>

 

            <div class="mySlides" style="width:100%; height:80%; position: relative;">

                <img src="Images/images1.jpg" style="width:100%; height:100%" />

                <div class="overlay">

                    <h4><b>Sattva Park Cubix</b></h4>

                    <p>DEvanahali, Benguular</p>

                    <h5><b>Rs. 43.63 L</b></h5>

                    <button class="btn btn-success">check Out</button>

                </div>

 

            </div>

 

        </div>



---------------------------------html for advertisement------------------



var myIndex = 0;

        carousel();

 

        function carousel() {

            var i;

            var x = document.getElementsByClassName("mySlides");

            for (i = 0; i < x.length; i++) {

                x[i].style.display = "none";

            }

            myIndex++;

            if (myIndex > x.length) { myIndex = 1 }

            x[myIndex - 1].style.display = "block";

            setTimeout(carousel, 2000); // Change image every 2 seconds

        }

[Yesterday 9:38 PM] Vaishnavi Rastogi

--------------------------------script file for it-----------------------

[Yesterday 9:39 PM] Vaishnavi Rastogi

.mySlides {

            display: none;

        }

 

        .overlay {

            position: absolute;

            bottom: 0;

            background: rgb(0, 0, 0);

            background: rgba(0, 0, 0, 0.5); /* Black see-through */

            color: #f1f1f1;

            width: 100%;

            transition: .5s ease;

            opacity: 0;

            color: white;

            font-size: 20px;

            padding: 20px;

            text-align: center;

        }

 

        .bbClass:hover .overlay {

            opacity: 1;

        }



----------------------css code for it----------------
