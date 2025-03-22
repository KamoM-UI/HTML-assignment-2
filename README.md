# HTML-assignment-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hi! PLP</title>
</head>
<body>
    <h1>Advanced HTML5 Elements and Forms</h1>
    <ol type ="I">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>PHP</li>
        <li>MySQL</li>
    </ol>
    <img src="https://images.pexels.com/photos/2127733/pexels-photo-2127733.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" 
     width="600" height="350" alt="image"><br>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John</td>
            <td>8813 Wintheiser Springs, Solchester, OH 94469</td>
            <td>+244 990 136 477</td>
            <td>xnormal@yahoo.ca</td>
        </tr>
        <tr>
            <td>Jeff</td>
            <td>31453 Vincent Crossing, Lakendrastad, WI 66077-8748</td>
            <td>+254 756 581945</td>
            <td>koudas@icloud.com</td>
        </tr>
        <tr>
            <td>Dave</td>
            <td>6453 Blick Flats, New Bernita, HI 93737</td>
            <td>+27 54 495 0305</td>
            <td>kawasaki@hotmail.com</td>
        </tr>
        <tr>
            <td>Eman</td>
            <td>741 Garrick Ford, Suite 308, PL98 8BZ, New Cleoland, Maine, Great Britain</td>
            <td>+1 505-646-5772</td>
            <td>vlefevre@gmail.com</td>
        </tr>
        <tr>
            <td>Olly</td>
            <td>342 Kihn Shoals, Suite 782, YK01 7XB, Elisaside, Maryland, Great Britain</td>
            <td>+234 702 918 6289</td>
            <td>paley@outlook.com</td>
        </tr><br>
    <h2>Registration Form</h2>
    <form>
        <label for="Name">Name:</label>
        <input type="text" id="Name" placeholder="Tinashe" required><br>

        <label for="Email">E-mail:</label>
        <input type="email" id="Email" placeholder="PLP@gmail.com" required><br>

        <label for="Password">Password:</label>
        <input type="password" id="Password" minlength="4" placeholder="1234" required><br>

        <label for="Date">Date:</label>
        <input type="date" id="Date" required><br>

        <label for="Gender">Gender:</label>

        <label for="Mr.">Mr.</label>
        <input type="radio" id="Male" value="Mr." name="gender" required>
        <label for="Mrs.">Mrs.</label>
        <input type="radio" id="Female" value="Mrs." name="gender" required><br>

        <label for="Continent">Continent:</label>
        <select id="Continent" required>
            <option value="Europe">Europe</option>
            <option value="Africa">Africa</option>
            <option value="Asia">Asia</option>
            <option value="America">America</option>
            <option value="Australia">Australia</option>
            <option value="Antarctica">Antarctica</option>
        </select><br>

        <label for="Not A Robot">Not A Robot:</label>
        <input type="checkbox" id="Not A Robot" required><br>


    </form><br> 
</body>
</html>
