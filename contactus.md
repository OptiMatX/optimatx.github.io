<html>
  <style>
  form {
  width: 50%;
  margin: 0 auto;
  padding: 20px;
  background-color: #f2f2f2;
  border-radius: 10px;
  box-shadow: 0 0 10px #ccc;
}

label {
  display: inline-block;
  margin-bottom: 5px;
  font-weight: bold;
}

input, textarea {
  display: block;
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-sizing: border-box;
  margin-bottom: 20px;
  font-size: 16px;
}

button[type="submit"] {
  background-color: #4CAF50;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}

button[type="submit"]:hover {
  background-color: #3e8e41;
}

  </style>
  <head>
    <meta charset="utf-8">
    <title>Contact Us</title>
  </head>
  <body>
    <h1>Contact Us</h1>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required><br>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="10" cols="30" required></textarea><br>

      <button type="submit">Submit</button>
    </form>
  </body>
</html>
