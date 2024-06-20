<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Contact Form</title>
    <link rel="stylesheet" href="style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Karla:ital,wght@0,200..800;1,200..800&display=swap" rel="stylesheet">
</head>
<body>

<center><h1>Contact Us</h2></center>

   <form action="/my-handling-form-page" method="post">
     <ul>
      <li>
      <label for="name">First Name</label>
      <input type="text" id="name" name="firstName" />
       <label for="lastName">Last Name</label>
       <input type="text" id="lastName" name="lastName" />
      <li>
      <label for="email">Email Address</label>
      <textarea id="email" name="email"></textarea>
      </li>
      <li>
     <label for="queryType">Query Type</label>
     <select id="queryType" name="queryType">
     <li><option value="option1">General Enquiry</option></li>
     <li><option value="option2">Support Request</option></li>
     </select>
    <li>
    <label for="message">Message</label>
    <textarea id="message" name="message"></textarea></li>

    <li><label for="contactConsent"> I consent to being contacted by the team To submit this form</label>
    <input type="checkbox" id="contactConsent" name="contactConsent"></li>

   <li class="button">  
  <button type="submit">Submit</button>  
   </li>  
   </form>

    
</body>
</html>
