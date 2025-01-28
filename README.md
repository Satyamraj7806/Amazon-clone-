# Amazon-clone-
i tried to make a clone of amazon homepage
// starting to create the page using html //

 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="amazon.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
</head>

<body>
    <header>
        <div class="navbar">
            <div class="navbarlogo border">
                <div class="logo"></div>
            </div>
             <div class="address border">
                <div class="delivery">
                    <p id="deliverto">Deliver to</p>
                    <div class="locationicon">
                        <i class="fa-solid fa-location-dot"></i>
                        <p id="india">INDIA</p>
                    </div>
                </div>
            </div>
             <div class="navsearch">
                <select class="searchselect">
                    <option>All</option>
                </select>
                <input id="searchbar" placeholder="Search Sattu">
                <div class="searchicon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
            <div class="country border">
                <div class="flagicon">
                    <i class="fa-solid fa-globe"></i>
                    <p class="countryname">IN</p>
                </div>
            </div>
            <div class="signin border">
                <p><span>Hello, sign in</span></p>
                <p class="navsecondclass">Accounts & Lists</p>
            </div>
            <div class="returns border">
                <p><span>Returns</span></p>
                <p class="navsecondclass">Orders</p>
            </div>
            <div class="navcart border">
                <i class="fa-solid fa-cart-shopping"></i>
            </div>
        </div>

