

<!DOCTYPE html>
<html lang="en">
<head>
<title>Telegram Weather Bot</title>
</head>
<body>
<h1>Telegram Weather Bot</h1>
<p>This is a simple Telegram bot that allows users to get weather details based on their location. The bot uses the OpenWeatherMap API to fetch weather data.</p>
<h2>Setup</h2>
<ol>
<li>Clone the repository:</li>
<pre><code>git clone https://github.com/Varshamishra56/TaskTrek_bot.git</code></pre>
<li>Install the required dependencies:</li>
<pre><code>pip install python-telegram-bot requests</code></pre>
<li>Create a <code>.env</code> file in the project directory and add your Telegram bot token and OpenWeatherMap API key:</li>
<pre><code>
OWM_API_KEY='f7302b3eb9834eb94608b4132ba447b6'</code></pre>
<li>Run the bot:</li>
<pre><code>
bot.py</code></pre>
</ol>
<h2>Commands</h2>
<ul>
<li><code>/start</code>: Start the bot and share your location to get weather details.</li>
<li><code>/help</code>: Get information about the bot and its commands.</li>
<li><code>/custom</code>: Execute a custom command (example command).</li>
</ul>
<h2>Usage</h2>
<p>Simply start a chat with the bot and share your location when prompted. The bot will fetch the weather details for your location and send them to you.</p>
<h2>Contributing</h2>
<p>Feel free to contribute to this project by submitting pull requests or reporting issues.</p>
</body>
</html>