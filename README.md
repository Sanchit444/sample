Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@Sanchit444 
Sanchit444
/
sample
Public
1
00
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
sample/form.html
@Sanchit444
Sanchit444 Add files via upload
Latest commit 49b0fcc 5 minutes ago
 History
 1 contributor
41 lines (40 sloc)  1.73 KB
   
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
    <link rel="stylesheet" href="form.css">
</head>
<body><div class="name">
    <form action="" method="get">
    <h1> Contact information</h1>
   <hr> <p> *Name:&nbsp;&nbsp; <input type="text" name="name" placeholder=" First Second Last" required>
    </p> <fieldset> <legend> Gender: </legend> <br> Male&nbsp;<input type="radio" name="Gender">&nbsp;Female<input type="radio" name="Gender"> 
    </fieldset><p>Address:&nbsp;&nbsp; <br><textarea name="Sanchit" id="Address" cols="30" rows="10" placeholder="Enter your address"></textarea></p>
        <p>email:<input type="email" name="email" id="Email"></p><br>
        <p>password:<input type="password"><br>
        </p><p>Pincode: <input type="number"></p>
    
    </p><h1>Payment information</h1>
    Card type 
    <select name="card tyoe" id="card type">
        <option value="">--Select a card type--</option>
        <option value="visa">visa</option>
        <option value="rupay">rupay</option>
        <option value="mastercard">mastercard</option>
    </select>
    <p>
       Card number <input type="number" name="card number" id="card number">
    </p>
    <p>
        Exp date <input type="date" name="date" id="date">
    </p>
    <p>
        CVV <input type="password" name="cvv" id="cvv">
    </p><p>
        <input type="submit" value="Pay now">
    </p></form></div>
    <input id="input" type="search" autocomplete="off" spellcheck="false" role="combobox" aria-live="polite" placeholder="Search Google or type a URL">
</body>
</html>
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
