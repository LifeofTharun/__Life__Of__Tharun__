<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/png" href="https://cdn.freebiesupply.com/logos/large/2x/weather-ios-logo-png-transparent.png">
</head>
<body>
    <main>
        <form>
            <input type="text" id="name" autocomplete="off">
            <button>
                <i class="fa-solid fa-magnifying-glass"></i>
            </button>
        </form>
        <section class="result">

            <figure class="name">
                <figcaption>Lo1ndon</figcaption> 
                <img src="https://flagsapi.com/GB/shiny/32.png">
            </figure>

            <figure class="temperature">
                <img src="https://openweathermap.org/img/wn/10d@4x.png">
                <figcaption>
                    <span>31</span>
                    <sup>o</sup>
                </figcaption> 
            </figure>
            <p class="description">overcast clouds</p>
            <ul>
                <li>
                    <span>clouds</span>
                    <i class="fa-solid fa-cloud"></i>
                    <span id="clouds">98</span>%
                </li>
                <li>
                    <span>humidity</span>
                    <i class="fa-solid fa-droplet"></i>
                    <span id="humidity">98</span>%
                </li>
                <li>
                    <span>pressure</span>
                    <i class="fa-solid fa-gauge"></i>
                    <span id="pressure">1011</span>hPa
                </li>
            </ul>
        </section>
    </main>

      <footer>
        <p>Created by Tharun B</p>
        <a href="https://www.linkedin.com/in/tharun-b-913030316?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app/" target="_blank">
            <i class="fa-brands fa-linkedin"></i>
        </a>
        <a href="https://github.com/LifeOfTharun" target="_blank">
            <i class="fa-brands fa-github"></i>
        </a>
    </footer>

    <script src="app.js"></script>
</body>
</html>
