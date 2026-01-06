<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Fallwerk: Tatort Campingplatz Ganterbach</title>

<!-- Confetti Library -->
<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>

<style>
body {
    font-family: Arial, sans-serif;
    background: #111;
    color: #fff;
    text-align: center;
    padding: 20px;
}

h1 {
    margin-bottom: 10px;
}

#quiz {
    max-width: 700px;
    margin: auto;
    background: #222;
    padding: 20px;
    border-radius: 10px;
}

.answer {
    display: block;
    background: #333;
    margin: 8px 0;
    padding: 10px;
    border-radius: 6px;
    cursor: pointer;
}

.answer:hover {
    background: #555;
}

#message {
    margin-top: 15px;
    font-size: 1.2em;
}

button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 1em;
    cursor: pointer;
}
</style>
</head>

<body>

<h1>Fallwerk: Tatort Campingplatz Ganterbach</h1>
<p id="progress"></p>

<div id="quiz">
    <h2 id="question"></h2>
    <div id="answers"></div>
    <div id="message"></div>
</div>

<script>
const quiz = [
    {
        question: "Frage 1: Was wurde am Tatort zuerst entdeckt?",
        answers: [
            "Ein zerbrochenes Handy",
            "Eine Blutspur",
            "Ei
