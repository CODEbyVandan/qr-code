<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Cute Arrest</title>
</head>
<body>
  <div class="cute-arrest">
    <h1>You are under arrest for being too cute</h1>
    <p>🚨😊🌟🎀</p>
  </div>
</body>
</html>

body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  background-color: #f9f9f9;
}

.cute-arrest {
  text-align: center;
  font-family: 'Comic Sans MS', cursive, sans-serif; /* Choose a cute font */
  color: #ff80bf; /* Cute pink color */
  animation: bounce 1s infinite alternate; /* Animation added */
}

h1 {
  font-size: 2em;
  margin-bottom: 20px;
}

p {
  font-size: 2em;
}

@keyframes bounce {
  to {
    transform: translateY(-30px);
  }
}
