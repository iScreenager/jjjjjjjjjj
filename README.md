<div class="card shadow p-3 mb-5 bg-white rounded" style="width: 25rem;">
            <img class="card-img-top" src="Images/images.jpg" alt="Card image cap">
            <div class="card-body text-center">
                <h3><b>Sattva Park Cubix</b></h3>
                <p>DEvanahali, Benguular</p>
                <h5><b>Rs. 43.63 L</b></h5>
                <div >
                <button type="button" class="btn btn-danger mt-3">Proceed</button>
                </div>
            </div>
        </div>



<!DOCTYPE html>
<html>
<head>
    <title>Infinite Slider</title>
    <style>
        .slider {
            display: flex;
            overflow-x: scroll;
            scroll-behavior: smooth;
        }
        
        .card {
            width: 25rem;
            margin-right: 1rem;
        }
        
        .card-img-top {
            height: 200px;
            object-fit: cover;
        }
        
        .card-body {
            padding: 1rem;
        }
    </style>
</head>
<body>
    <div class="slider">
        <div class="card shadow p-3 mb-5 bg-white rounded">
            <img class="card-img-top" src="Images/images.jpg" alt="Card image cap">
            <div class="card-body text-center">
                <h3><b>Sattva Park Cubix</b></h3>
                <p>Devanahalli, Bengaluru</p>
                <h5><b>Rs. 43.63 L</b></h5>
                <div>
                    <button type="button" class="btn btn-danger mt-3">Proceed</button>
                </div>
            </div>
        </div>
        
        <!-- Add more card elements here -->
        
    </div>
    
    <script>
        // Infinite slider logic
        const slider = document.querySelector('.slider');
        const cards = document.querySelectorAll('.card');
        const cardWidth = cards[0].offsetWidth;
        const previousButton = document.createElement('button');
        const nextButton = document.createElement('button');
        
        previousButton.innerHTML = '&lt;'; // Previous icon
        nextButton.innerHTML = '&gt;'; // Next icon
        
        previousButton.addEventListener('click', () => {
            slider.scrollBy(-cardWidth, 0);
        });
        
        nextButton.addEventListener('click', () => {
            slider.scrollBy(cardWidth, 0);
        });
        
        slider.appendChild(previousButton);
        slider.appendChild(nextButton);
    </script>
</body>
</html>
