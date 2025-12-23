<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Birthday 🎉</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  text-align: center;
  overflow: hidden;
}
.section {
  display: none;
  padding: 40px 20px;
  animation: fadeIn 1.5s ease;
}
.section.active {
  display: block;
}
h1, h2 {
  color: #fff;
}
img {
  max-width: 220px;
  border-radius: 20px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.3);
}
button {
  margin-top: 30px;
  padding: 14px 28px;
  border: none;
  border-radius: 30px;
  font-size: 18px;
  background: #ff4081;
  color: white;
  cursor: pointer;
}
button:hover {
  background: #e91e63;
}
.cake {
  font-size: 120px;
}
.candle {
