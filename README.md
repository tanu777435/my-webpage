# my-webpage
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="welcome-container">
    <h1>Welcome to MedInfo</h1>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="login-container">
    <h1>Login Page</h1>
    <div class="login-box">
      <h2>Patient Login</h2>
      <form action="#">
        <input type="text" placeholder="Username" required>
        <input type="passwor…
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, sans-serif;
}

.welcome-container {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(135deg, #ff7e5f, #feb47b, #86a8e7, #7f7fd5);
  color: white;
  text-align: center;
}

h1 {
  font-size: 3em;
}
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, sans-serif;
}

.login-container {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: linear-gradient(135deg, #ff7e5f, #feb47b, #86a8e7, #7f7fd5);
  color: white;
  text-align: center;
}

h1 {
  font-size: 3em;
}

.login-box {
  background-color: rgba(255, 255, 255, 0.1);
  padding: 20px;
  margin: 10px;
  border-radius: 10px;
  width: 300px;
}

h2 {
  font-size: 1.5em;
}

form {
  display: flex;
  flex-direction: column;
}

input {
  padding: 10px;
  margin: 5px 0;
  border: none;
  border-radius: 5px;
  font-size: 1em;
}

button {
  padding: 10px;
  margin: 5px 0;
  border: none;
  border-radius: 5px;
  font-size: 1em;
  background-color: #86a8e7;
  color: white;
  cursor: pointer;
}

button:hover {
  background-color: #7f7fd5;
}
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, sans-serif;
}

.patient-container {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: linear-gradient(135deg, #ff7e5f, #feb47b, #86a8e7, #7f7fd5);
  color: white;
  text-align: center;
  padding: 20px;
}

h1 {
  font-size: 3em;
  margin-bottom: 20px;
}

.section {
  background-color: rgba(255, 255, 255, 0.1);
  padding: 20px;
  margin: 10px;
  border-radius: 10px;
  width: 80%;
}

h2 {
  font-size: 2em;
  margin-bottom: 10px;
}

table {
  width: 100%;
  border-collapse: collapse;
}

th, td {
  padding: 10px;
  border: 1px solid white;
}

button {
  padding: 10px;
  margin-top: 10px;
  border: none;
  border-radius: 5px;
  font-size: 1em;
  background-color: #86a8e7;
  color: white;
  cursor: pointer;
}

button:hover {
  background-color: #7f7fd5;
}
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, sans-serif;
}

header {
  background-color: #333;
  color: white;
  padding: 10px;
  text-align: center;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 10px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

main {
  padding: 20px;
  background: linear-gradient(135deg, #ff7e5f, #feb47b, #86a8e7, #7f7fd5);
  color: white;
  text-align: center;
}

section {
  margin-bottom: 20px;
}

footer {
  background-color: #333;
  color: white;
  padding: 10px;
  text-align: center;
  position: fixed;
  width: 100%;
  bottom: 0;
}
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, sans-serif;
}

.doctor-container {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: linear-gradient(135deg, #ff7e5f, #feb47b, #86a8e7, #7f7fd5);
  color: white;
  text-align: center;
  padding: 20px;
}

h1 {
  font-size: 3em;
  margin-bottom: 20px;
}

.section {
  background-color: rgba(255, 255, 255, 0.1);
  padding: 20px;
  margin: 10px;
  border-radius: 10px;
  width: 80%;
}

h2 {
  font-size: 2em;
  margin-bottom: 10px;
}

table {
  width: 100%;
  border-collapse: collapse;
}

th, td {
  padding: 10px;
  border: 1px solid white;
}
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, sans-serif;
}

.logout-container {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: linear-gradient(135deg, #ff7e5f, #feb47b, #86a8e7, #7f7fd5);
  color: white;
  text-align: center;
}

h1 {
  font-size: 3em;
  margin-bottom: 20px;
}

.logout-box {
  background-color: rgba(255, 255, 255, 0.1);
  padding: 20px;
  margin: 10px;
  border-radius: 10px;
  width: 300px;
}

h2 {
  font-size: 1.5em;
}

button {
  padding: 10px;
  margin-top: 10px;
  border: none;
  border-radius: 5px;
  font-size: 1em;
  background-color: #86a8e7;
  color: white;
  cursor: pointer;
}

button:hover {
  background-color: #7f7fd5;
}
