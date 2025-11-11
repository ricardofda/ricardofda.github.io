<html>
<head>
  <style>
    form > * { display: block; }
  </style>
</head>
<body>
  <form action="done.html">
    <label for="email">email</label>
    <input type="text" name="email" />
    <label for="password">password</label>
    <input type="password" name="password" />
    <label for="otp">otp</label>
    <input type="text" name="otp" autocomplete="one-time-code" />
    <button type="submit">submit</button>
  </form>
</body>
</html>
