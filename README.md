# Product Table
## Date:07.07.2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="style.css">
  <title>Product Table</title>
</head>
<body>

  <h1>Product Catalog</h1>

  <table border="1">
    <caption>Latest Tech Gadgets</caption>

    <thead>
      <tr>
        <th>Product Name</th>
        <th>Product Price</th>
        <th>Description</th>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td>Wireless Earbuds</td>
        <td>₹2,499</td>
        <td>Compact earbuds with noise cancellation and 20-hour battery life</td>
      </tr>
      <tr>
        <td>Mechanical Keyboard</td>
        <td>₹3,200</td>
        <td>RGB backlit keys with tactile feedback, perfect for typing and gaming</td>
      </tr>
      <tr>
        <td>Webcam</td>
        <td>₹1,499</td>
        <td>1080p full HD webcam with built-in microphone for video calls</td>
      </tr>
      <tr>
        <td>USB-C Hub</td>
        <td>₹999</td>
        <td>Multiport adapter with HDMI, USB, and SD card reader support</td>
      </tr>
      <tr>
        <td>Graphic Tablet</td>
        <td>₹5,599</td>
        <td>Digital drawing pad with pressure-sensitive stylus and USB connectivity</td>
      </tr>
    </tbody>
  </table>

</body>
</html>
```
```
body {
  background-color: #f4f7f9;
  font-family: sans-serif;
  margin: 0;
  padding: 40px;
}

h1 {
  text-align: center;
  font-size: 2.4em;
  color: #2e3a59;
  margin-bottom: 30px;
  text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.05);
}

table {
  width: 85%;
  margin: auto;
  border-collapse: collapse;
  border-radius: 10px;
  overflow: hidden;
  background-color: #ffffff;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.07);
  transition: transform 0.3s ease;
}

table:hover {
  transform: scale(1.005);
}

caption {
  caption-side: top;
  font-weight: bold;
  font-size: 1.3em;
  padding: 10px 0;
  color: #4b6584;
  text-align: center;
}

thead th {
  background-color: #b8d8e4; 
  color: #1e272e;
  padding: 14px;
  text-align: center;
  font-size: 1.05em;
}

tbody td {
  border: 1px solid #e1e7ec;
  padding: 12px;
  font-size: 0.95em;
  color: #34495e;
  text-align: center;
}

tbody tr:nth-child(even) {
  background-color: #f6f9fb; 
}

tbody tr:nth-child(odd) {
  background-color: #ffffff;
}

tbody tr:hover {
  background-color: #dceef2; 
  cursor: pointer;
  transition: background-color 0.3s ease;
}

td, th {
  word-wrap: break-word;
}
```
## Output:

![image](https://github.com/user-attachments/assets/60ab8f6b-15a4-4b51-a52d-a9edea725268)

![image](https://github.com/user-attachments/assets/d1df37f1-95ab-4668-a1f5-cf315788a62a)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
