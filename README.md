<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>
    <h1>ISS Overhead Notifier</h1>

  <h2>Overview</h2>
    <p>This Python script checks if the International Space Station (ISS) is overhead a specified location during nighttime and sends email notifications accordingly.</p>

  <h2>Features</h2>
    <ul>
        <li>Utilizes Python's smtplib module for email sending.</li>
        <li>Integrates with ISS position and sunrise-sunset APIs for accurate visibility assessment.</li>
        <li>Customizable: Adjust latitude, longitude, and email credentials as needed.</li>
    </ul>

  <h2>How to Use</h2>
<ol>
    <li>Ensure Python is installed on your system.</li>
    <li>Clone the repository or download the script. Use the following command to clone:</li>
    <code>git clone https://github.com/Manjunathhs-0003/ISS-Overhead.git</code>
    <li>Add your mail id and password in MY_EMAIL and MY_PASSWORD respectively.</li>
    <li>Run the script using Python.</li>
    <li>Relax and receive email alerts when the ISS is visible at your location during nighttime!</li>
</ol>


  <h2>File Structure</h2>
    <ul>
        <li><code>main.py</code>: Main Python script.</li>
    </ul>

   <h2>Dependencies</h2>
    <ul>
        <li>Python 3.x</li>
        <li>requests</li>
        <li>smtplib (Standard Library)</li>
        <li>time (Standard Library)</li>
    </ul>

  <p>Contributions and issue reports are welcome!</p>
  <p>If you want to automate this code to run automatically using PythonAnywhere or crontab, you can contact the project owner for assistance.</p>
</body>
</html>
