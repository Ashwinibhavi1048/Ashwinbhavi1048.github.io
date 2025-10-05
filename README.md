body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(to right, #ffecd2 0%, #fcb69f 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
}

.container {
  background: white;
  padding: 40px;
  border-radius: 15px;
  box-shadow: 0 8px 16px rgba(0,0,0,0.2);
  max-width: 500px;
}

h1 {
  color: #d6336c;
  font-size: 2.5em;
}

.message {
  font-size: 1.2em;
  margin: 20px 0;
}

.buttons button {
  font-size: 1.2em;
  margin: 10px;
  padding: 10px 20px;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}

.buttons button:hover {
  opacity: 0.8;
}

button:first-child {
  background-color: #ff69b4;
  color: white;
}

button:last-child {
  background-color: #ccc;
}

.response {
  margin-top: 30px;
  font-size: 1.5em;
  font-weight: bold;
}
