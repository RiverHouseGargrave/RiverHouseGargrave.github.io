# RiverHouseGargrave.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>River House | Luxury Riverside Cottage in the Yorkshire Dales</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: Arial, Helvetica, sans-serif;
    line-height:1.6;
    color:#333;
}

.hero{
    height:100vh;
    background:url('river-house-main.jpg') center/cover no-repeat;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
    position:relative;
}

.hero::before{
    content:'';
    position:absolute;
    inset:0;
    background:rgba(0,0,0,0.45);
}

.hero-content{
    position:relative;
    z-index:1;
    max-width:800px;
    padding:20px;
}

.hero h1{
    font-size:4rem;
    margin-bottom:10px;
}

.hero p{
    font-size:1.4rem;
}

.btn{
    display:inline-block;
    margin-top:25px;
    padding:14px 28px;
    background:#2e6b5c;
    color:white;
    text-decoration:none;
    border-radius:4px;
}

section{
    padding:80px 10%;
}

h2{
    margin-bottom:20px;
    color:#2e6b5c;
}

.about{
    background:#f8f8f8;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:8px;
    box-shadow:0 2px 10px rgba(0,0,0,0.08);
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:15px;
}

.gallery img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:8px;
}

.location{
    background:#f8f8f8;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:40px 20px;
}
</style>
</head>

<body>

<header class="hero">
    <div class="hero-content">
        <h1>River House</h1>
        <p>Luxury Riverside Holiday Cottage in Gargrave, North Yorkshire</p>
        <a href="#" class="btn">View on Airbnb</a>
    </div>
</header>

<section class="about">
    <h2>Welcome to River House</h2>

    <p>
        Nestled on the banks of the River Aire in the charming village of Gargrave,
        River House is a beautifully restored Victorian stone house offering luxury
        accommodation for up to six guests.
    </p>

    <br>

    <p>
        Completely renovated in 2024, the property combines period character with
        modern comfort. Enjoy uninterrupted river views, spacious open-plan living,
        a private garden, outdoor dining areas, and easy access to some of the most
        spectacular scenery in the Yorkshire Dales.
    </p>
</section>

<section>
    <h2>Highlights</h2>

    <div class="features">
        <div class="card">
            <h3>Riverfront Setting</h3>
            <p>Direct views over the River Aire with private riverside garden access.</p>
        </div>

        <div class="card">
            <h3>Sleeps 6 Guests</h3>
            <p>Three comfortable bedrooms and spacious living areas.</p>
        </div>

        <div class="card">
            <h3>Village Location</h3>
            <p>Walk to pubs, restaurants, shops and Gargrave railway station.</p>
        </div>

        <div class="card">
            <h3>Perfect for Walkers</h3>
            <p>Easy access to the Pennine Way, Malham Cove and the Yorkshire Dales.</p>
        </div>

        <div class="card">
            <h3>Outdoor Living</h3>
            <p>Patio dining area overlooking the river and south-facing garden.</p>
        </div>

        <div class="card">
            <h3>Luxury Renovation</h3>
            <p>Underfloor heating, modern kitchen and stylish interiors throughout.</p>
        </div>
    </div>
</section>

<section>
    <h2>Gallery</h2>

    <div class="gallery">
        <img src="photo1.jpg" alt="River House Exterior">
        <img src="photo2.jpg" alt="Living Room">
        <img src="photo3.jpg" alt="River View">
        <img src="photo4.jpg" alt="Dining Area">
        <img src="photo5.jpg" alt="Bedroom">
        <img src="photo6.jpg" alt="Garden">
    </div>
</section>

<section class="location">
    <h2>Explore the Yorkshire Dales</h2>

    <p>
        River House is perfectly positioned for discovering the Yorkshire Dales.
        Popular destinations nearby include:
    </p>

    <br>

    <ul>
        <li>Malham Cove</li>
        <li>Bolton Abbey</li>
        <li>Grassington</li>
        <li>Settle</li>
        <li>Ribblehead Viaduct</li>
        <li>Skipton Castle</li>
    </ul>
</section>

<section>
    <h2>Book Your Stay</h2>

    <p>
        For availability, pricing and guest reviews, please visit our Airbnb listing.
    </p>

    <a href="#" class="btn">View Airbnb Listing</a>
</section>

<footer>
    <h3>River House, Gargrave</h3>
    <p>Luxury Riverside Accommodation in the Yorkshire Dales</p>
</footer>

</body>
</html>

A few additions would make it look much more premium:

Use a full-width hero photo from the river-facing side of the house.
Add a gallery slider rather than static images.
Embed a Google Map.
Add a section called "Guest Reviews" pulling selected Airbnb quotes.
Include a "Things To Do" section with walking routes, pubs, and local attractions around Gargrave and the Dales
