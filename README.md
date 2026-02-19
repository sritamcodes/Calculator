<h1 align="center">🧮 Calculate Me!</h1>

<p align="center">
A responsive web-based calculator built using HTML, CSS, and Vanilla JavaScript.
It performs basic arithmetic operations and dynamically evaluates expressions entered through button clicks.
</p>

<h3>🚀 Features</h3>

<p>
• Addition (+)<br>
• Subtraction (−)<br>
• Multiplication (*)<br>
• Division (/)<br>
• Percentage (%)<br>
• Decimal Support (.)<br>
• Clear (C)<br>
• Real-time display updates
</p>

<h3>🛠 Tech Stack</h3>

<p>
HTML5 – Structure<br>
CSS3 – Styling & Layout<br>
JavaScript (ES6) – Logic & DOM Manipulation<br>
Google Fonts – Roboto & Ubuntu
</p>

<h3>📂 Project Structure</h3>

<pre>
Calculate-Me/
│── index.html
│── style.css
│── utils.css
│── script.js
│── README.md
</pre>

<h3>⚙️ How It Works</h3>

<p>
All buttons are selected using <code>document.querySelectorAll('.button')</code>.<br>
Click events are attached dynamically to each button.<br>
The expression is built as a string.<br>
When "=" is pressed, <code>eval()</code> evaluates the expression.<br>
Pressing "C" clears the display.
</p>

<h3>▶️ How to Run</h3>

<p>
1. Copy this link and run in your browser<br>
https://sritamcodes.github.io/Calculator/

<h3>⚠️ Important Note</h3>

<p>
This project uses JavaScript's <code>eval()</code> function for expression evaluation.
It is suitable for learning purposes but not recommended for production applications.
</p>

<h3>🔮 Future Improvements</h3>

<p>
• Implement working memory functions (M+, M-, MC)<br>
• Add keyboard input support<br>
• Improve error handling<br>
• Replace <code>eval()</code> with a safer parser<br>
• Add dark mode
</p>

<h3>📄 License</h3>

<p>
This project is open-source and free to use.
</p>
