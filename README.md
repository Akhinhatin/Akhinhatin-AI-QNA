# Akhinhatin-AI-QNA
Interactive AI Q&amp;A website built with HTML CSS,and JavaScript 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Q&A</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>AI Q&A</h1>
  </header>

  <main>
    <div id="chatbox">
      <div class="bot-message">Hello! Ask me anything. 🤖</div>
    </div>
    <input id="userInput" type="text" placeholder="Type your question...">
    <button onclick="sendMessage()">Send</button>
  </main>

  <script src="script.js"></script>
</body>
</html>
