# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SunPharma</title>
    <style>
        header {
            background-color: #f1f1f1;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            width: 100px; 
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        .cards {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        
        .card {
            width: 200px;
            padding: 10px;
            margin: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            text-align: center;
        }
        
        .card img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="sunpharma_logo.png" alt="SunPharma Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products Focus</a></li>
                <li><a href="#">Innovations</a></li>
                <ul>
                    <li><a href='#'>Generic Research</a></li>
                    <li><a href='#'>New Drug Discovery</a></li>
                    <li><a href='#'>Opportunities</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <div class="cards">
        <div class="card">
            <img src="image1.jpg" alt="Image 1">
            <p>Innovation</p>
            <p>Science is at the heart of Sun Pharma Our scientists work closely with doctors patients, and business development teams to generate Innovative concepts and ideas to harreal market reeds and synergies across therapeutic areas.</p>
            <button>Read More</button>
        </div>
        <div class="card">
            <img src="image2.jpg" alt="Image 2">
            <p>Quality</p>
            <p>Our vision is to globalize, harmonize and simplify GxP processes to achieve a sustainable quality culture.</p>
            <button>Read More</button>
        </div>
        <div class="card">
            <img src="image3.jpg" alt="Image 3">
            <p>Careers</p>
            <p>We hire exceptionaly talented Individuals and ensure they are nurtured professionally Dur multi-dimensional work environment offers high growth opportunities through challenging roles with clear responsibilities.</p>
            <button>Read More</button>
        </div>
        <div class="card">
            <img src="image4.jpg" alt="Image 4">
            <p>Responsibility</p>
            <p>Our CSR efforts are focused on serving and helping needy and underprivileged communities. Our priority areas include health, education, drinking water and sanitarion</p>
            <button>Read More</button>
        </div>
    </div>

    <footer>
        Designed and Developed by NAMITHA @ 2024
    </footer>
</body>
</html>
```
## OUTPUT:
![resweb](https://github.com/NamithaS2710/Pharma/assets/133190822/3c66931d-16f0-4ba2-a9a1-da65e8708c2b)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
