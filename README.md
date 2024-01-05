# wad-lab-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            color:rgb(0, 251, 255);
            background-color:black;

        }

        .row {
            display: flex;
            width: 100%;
            box-sizing: border-box;
        }

        .column {
            flex: 1;
            padding: 20px;
        }

        .logo {
            max-width: 30%;
            height: auto;
        }

        .header {
            text-align: center;
        }

        .links {
            display: flex;
            justify-content: space-around;
            padding: 10px;
            background-color: rgb(234, 122, 128);
        
        }
        


        .links a {
            text-decoration: none;
            color: #863d18;
            padding: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            border-color: rgb(0, 128, 122);
            background-color: palegreen;
            
        }

        .services {
            display: flex;
            flex-direction: column;
        }
    </style>
</head>
<body>

    <div class="row">
        
        <div class="column">
            <img src="flipkart.jpg" alt="Logo" class="logo">
        </div>

       
        <div class="column header">
            <h1>Flipkart</h1>
        </div>
    </div>
    <div class="row links">
        <a href="https://www.flipkart.com/">Home</a>
        <a href="https://www.flipkart.com/account/login">Login</a>
        <a href="#https://www.flipkart.com/register">Registration</a>
        <a href="https://www.flipkart.com/premium-catalog/">Catalogue</a>
        <a href="https://www.flipkart.com/rv/viewcart">Cart</a>
        <a href="https://www.flipkart.com/helpcentre">Contact Us</a>
    </div>

   
    <div class="row">
        <div class="column services">
            <a href="https://www.flipkart.com/">Notification Preferances</a>
            <a href="https://advertising.flipkart.com/login">advertise</a>
            <a href="https://www.flipkart.com/helpcentre">24x7 support</a>
           
        </div>

        <div class="column">
            <p>Wide Range of Genuine Products, Easy Returns, Cash on Delivery, Browse Now! Best Place for Safe Online Shopping.</p>
        </div>
    </div>

</body>
</html>



