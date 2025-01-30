# mmt-webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Make Trip</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url("waterfall.jpg");
        }

        header {
            background-color: #003580;
            color: white;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        /* Logo styling */
        .logo img {
            width: 120px; /* Adjust logo size */
            height: auto;
        }

        header nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        header nav ul li {
            margin-right: 20px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        .user-actions a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        main {
            padding: 20px;
        }

        .search-section {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .tabs {
            display: flex;
            margin-bottom: 20px;
        }

        .tabs button {
            background-color: #f4f4f4;
            border: none;
            padding: 10px 20px;
            margin-right: 10px;
            cursor: pointer;
            border-radius: 4px;
        }

        .tabs button.active {
            background-color: #003580;
            color: white;
        }

        .search-options {
            display: flex;
            flex-direction: column;
        }

        .trip-type {
            display: flex;
            margin-bottom: 20px;
        }

        .trip-type button {
            background-color: #f4f4f4;
            border: none;
            padding: 10px 20px;
            margin-right: 10px;
            cursor: pointer;
            border-radius: 4px;
        }

        .trip-type button.active {
            background-color: #003580;
            color: white;
        }

        .search-fields {
            display: flex; 
            flex-wrap: wrap; 
            gap: 20px; 
            margin-bottom: 20px; 
        }

        .field {
           flex: 1; 
           min-width: 200px; 
       }
       
       .field label {
           display: block; 
           margin-bottom: 5px; 
           font-weight: bold; 
       }
       
       .field input,
       .field select {
           width: 100%; 
           padding: 10px; 
           border: 1px solid #ccc; 
           border-radius: 4px; 
           font-size: 16px;
       }

       .field select {
           appearance: none; /* Remove default arrow */
           background-color: white;
           cursor: pointer;
       }
       
       .special-fares {
           margin-bottom: 20px; 
       }
       
       .special-fares label {
           display: block; 
           margin-bottom: 10px; 
           font-weight: bold; 
       }
       
       .fares {
           display: flex; 
           gap: 10px; 
       }
       
       .fares button {
           background-color: #f4f4f4; 
           border: none; 
           padding: 10px 20px; 
           cursor: pointer; 
           border-radius: 4px; 
       }
       
       .search-button {
           background-color: #003580; 
           color: white; 
           border: none; 
           padding: 15px 30px; 
           cursor: pointer; 
           border-radius: 4px; 
           width: 100%; 
           font-size: 16px; 
       }
       
       .search-button:hover {
           background-color: #002366; 
       }
    </style>
</head>
<body>
    <header>
        <!-- Logo Section -->
        <div class="logo">
            <img src="C:\Users\admin\OneDrive\Pictures\maketrip.png" background-color: white;>
        </div>

        <nav>
            <ul>
                <li><a href="#">List Your Property</a></li>
                <li><a href="#">Grow your Business!</a></li>
                <li><a href="#">Biz</a></li>
                <li><a href="#">Introducing my Biz</a></li>
                <li><a href="#">Business Travel Solutions</a></li>
            </ul>
        </nav>
        <div class="user-actions">
            <a href="#">My Trip</a>
            <a href="#">Message your bookings</a>
            <a href="#">Login</a>
            <a href="#">Create Account</a>
        </div>
    </header>

    <main>
        <section class="search-section">
             <div class="tabs">
                <button class="active" style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/airplane-take-off.png" alt="Flights" style="width:16px;height:auto;"> Flights
                </button>
                <button style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/hotel.png" style="width:16px;height:auto;"> Hotels
                </button>
                <button style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/home.png" style="width:16px;height:auto;"> Homestays & Villas
                </button>
                <button style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/tourist.png" style="width:16px;height:auto;"> Holiday Packages
                </button>
                <button style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/train.png" alt="Trains" style="width:16px;height:auto;"> Trains
                </button>
                <button style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/bus.png" alt="Buses" style="width:16px;height:auto;"> Buses
                </button>
                <button style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/taxi.png" alt="Cabs" style="width:16px;height:auto;"> Cabs
                </button>
                <button style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/money.png" alt="Forex Card & Currency" style="width:16px;height:auto;"> Forex Card & Currency
                </button>
                <button style="background-color: #00008B; color: white; border: none; padding: 10px;">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/shield.png" alt="Travel Insurance" style="width:16px;height:auto;"> Travel Insurance
                </button>
             </div>

             <div class="search-options">
                 <div class="trip-type">
                     <button class="active" style="background-color: #00008B; color: white; border: none; padding: 10px;">One Way</button>
                     <button style="background-color: #00008B; color: white; border: none; padding: 10px;">Round Trip</button>
                     <button style="background-color: #00008B; color: white; border: none; padding: 10px;">Multi City</button>
                 </div>

                 <div class="search-fields">
                     <div class="field">
                         <label for="from">From</label>
                         <input type="text" id="from" value="Delhi (DEL, Delhi Airport India)">
                     </div>

                     <div class="field">
                         <label for="to">To</label>
                         <input type="text" id="to" value="Bengaluru (BLR, Bengaluru International Airport ...)">
                     </div>

                     <div class="field">
                         <label for="departure-date">Departure Date</label>
                         <input type="date" id="departure-date">
                     </div>

                     <div class="field">
                         <label for="return-date">Return Date</label>
                         <input type="date" id="return-date" disabled>
                     </div>

                     <div class="field">
                         <label for="travellers">Travellers</label>
                         <select id="travellers">
                             <option value="1">1 Traveller</option>
                             <option value="2">2 Travellers</option>
                             <option value="3">3 Travellers</option>
                             <option value="4">4 Travellers</option>
                             <option value="5">5 Travellers</option>
                             <option value="6">6 Travellers</option>
                             <option value="7">7 Travellers</option>
                             <option value="8">8 Travellers</option>
                             <option value="9">9 Travellers</option>
                             <option value="10">10 Travellers</option>
                         </select>
                     </div>

                     <div class="field">
                         <label for="seat-type">Seat Type</label>
                         <select id="seat-type">
                             <option value="economy">Economy</option>
                             <option value="premium-economy">Premium Economy</option>
                             <option value="business">Business</option>
                             <option value="first-class">First Class</option>
                         </select>
                     </div>
                 </div>

                 <div class="special-fares">
                     <label>Select a special fare</label>
                     <div class="fares">
                         <button>EXTRASAVINGS</button>
                         <button>Regular</button>
                         <button>Student</button>
                         <button>Senior Citizen</button>
                         <button>Armed Forces</button>
                         <button>Doctor and Nurses</button>
                     </div>
                 </div>

                 <button class="search-button">SEARCH</button>
             </div>
         </section>
     </main>

     <script>
         // Enable/disable return date based on trip type
         const tripTypeButtons = document.querySelectorAll('.trip-type button');
         const returnDateInput = document.getElementById('return-date');

         tripTypeButtons.forEach(button => {
             button.addEventListener('click', () => {
                 if (button.textContent === 'One Way') {
                     returnDateInput.disabled = true;
                 } else {
                     returnDateInput.disabled = false;
                 }
             });
         });
     </script>
</body>
</html>
