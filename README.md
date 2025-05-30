
<title>Calculator README</title>
<style>
  body {
    font-family: Arial, sans-serif;
    line-height: 1.5;
    max-width: 700px;
    margin: 2rem auto;
    padding: 0 1rem;
    background-color: #f9f9f9;
    color: #222;
  }
  h1, h2 {
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }
  h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }
  h2 {
    font-size: 1.8rem;
    margin-top: 2rem;
    margin-bottom: 0.75rem;
    color: #444;
  }
  /* Optional: style emojis slightly bigger */
  .emoji {
    font-size: 1.5rem;
  }
</style>
</head>
<body>
<h1><span class="emoji">🧮</span> Calculator</h1>
<h2><span class="emoji">✨</span> Features</h2>
<ul>
  <li>Basic arithmetic: add, subtract, multiply, divide ➕➖✖️➗</li>
  <li>Clear (<code>AC</code>) to reset everything 🧹</li>
  <li>Toggle sign (<code>+/-</code>) to switch positive/negative ➕➖</li>
  <li>Percentage (<code>%</code>) calculations 💯</li>
  <li>Square root (<code>√</code>) with error handling for negative numbers ✔️</li>
  <li>Decimal support for precise input 🔢</li>
  <li>Color-coded buttons for intuitive use</li>
  <li>Visual feedback on button presses 👆</li>
</ul>
<h2><span class="emoji">⚙️</span> How It Works</h2>
<p>
  Built using Java Swing components (<code>JFrame</code>, <code>JPanel</code>, <code>JButton</code>, <code>JLabel</code>)<br />
  Buttons arranged in a 5x4 grid layout with distinct colors by function<br />
  Users click buttons to input numbers and operators<br />
  Pressing <code>=</code> computes and updates the display<br />
  Handles errors gracefully (like invalid square root inputs)
</p>
<h2><span class="emoji">🚀</span> Usage</h2>
<ol>
  <li>Compile the <code>Calculator.java</code> file using your Java compiler.</li>
  <li>Run the program — a window with the calculator UI will appear.</li>
  <li>Click the buttons to perform calculations.</li>
</ol>
<h2><span class="emoji">📝</span> Code Highlights</h2>
<ul>
  <li>Custom color palette enhances the UI 🎨</li>
  <li>Clear separation of button categories for styling and behavior</li>
  <li>ActionListeners manage user input and calculation logic</li>
  <li>Helper methods like <code>clearAll()</code> and <code>removeZeroDecimal()</code> improve usability</li>
</ul>
<h2><span class="emoji">💻</span> Requirements</h2>
<p>Java Development Kit (JDK) 8 or newer</p>
<h2><span class="emoji">🌟</span> Future Ideas</h2>
<ul>
  <li>Keyboard input support ⌨️</li>
  <li>More advanced math functions (exponents, logs, etc.)</li>
  <li>UI improvements with themes and animations 🎭</li>
</ul>
</body>
</html>

Helper methods like clearAll() and removeZeroDecimal() improve usability
