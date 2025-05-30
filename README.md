<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
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

<h1>Issues and Bug Fixes</h1>
<img width="362" alt="Screenshot 2025-05-30 at 18 56 07" src="https://github.com/user-attachments/assets/be639f26-2bda-4389-95eb-037dd6eb13c2" />
<p>I noticed that when I was running the programm that the buttons on the calculator would not go to thier custom color that I had set for them. The issue was becasue I did not have the buttons set up correctly. They didn't have button.setOpaque. </p>
<img width="495" alt="Screenshot 2025-05-30 at 18 58 18" src="https://github.com/user-attachments/assets/89bc687e-46aa-41f9-b316-ab0ae3b7813d" />


<p>This was an easy fix once spotted.</p>
<img width="518" alt="Screenshot 2025-05-30 at 18 57 39" src="https://github.com/user-attachments/assets/c9b211b4-5e20-4a4a-a4dc-acaa94e59625" />
<img width="445" alt="Screenshot 2025-05-30 at 18 59 54" src="https://github.com/user-attachments/assets/e72f4b07-6ede-45da-9543-4c5cf75a771e" />

<h1>Here is the final product!</h1>
https://github.com/user-attachments/assets/ffb5fe3b-4e0c-47ce-ad2a-b347ff750fb0

</body>
</html>
