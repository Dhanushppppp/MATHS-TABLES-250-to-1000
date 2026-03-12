<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Python Multiplication Tables (251–1000)</title>
</head>
<body>

<h1>📘 Python Multiplication Tables (251 to 1000)</h1>

<p>
This project generates multiplication tables using <strong>Python</strong>.
It prints tables from <strong>251 to 1000</strong>, with each table displaying
multiplication from <strong>1 to 10</strong>.
</p>

<hr>

<h2>🚀 Project Overview</h2>
<ul>
  <li>Language: Python 🐍</li>
  <li>Concepts Used:
    <ul>
      <li>Loops (<code>for</code>)</li>
      <li>Formatted Strings (f-strings)</li>
      <li>Console Output</li>
    </ul>
  </li>
</ul>

<hr>

<h2>🧮 Python Code</h2>

<pre>
<code>
# Print multiplication tables from 251 to 1000

for num in range(251, 1001):
    print(f"\nMultiplication Table of {num}")
    print("-" * 30)
    for i in range(1, 11):
        print(f"{num} x {i} = {num * i}")
</code>
</pre>

<hr>

<h2>📌 Example Output</h2>

<pre>
Multiplication Table of 251
------------------------------
251 x 1 = 251
251 x 2 = 502
251 x 3 = 753
...
251 x 10 = 2510
</pre>

<hr>

<h2>▶️ How to Run</h2>
<ol>
  <li>Make sure Python is installed on your system</li>
  <li>Save the file as <code>tables.py</code></li>
  <li>Open terminal or command prompt</li>
  <li>Run:
    <pre><code>python tables.py</code></pre>
  </li>
</ol>

<hr>

<h2>📂 Use Case</h2>
<ul>
  <li>Learning Python loops</li>
  <li>Practicing number tables</li>
  <li>Beginner-friendly Python project</li>
</ul>

<hr>

<h2>🤝 Contribution</h2>
<p>
Feel free to fork this repository on :contentReference[oaicite:0]{index=0},
improve the code, or add features like file output or user input.
</p>

<hr>

<h3>⭐ If you like this project, don’t forget to star the repository!</h3>

</body>
</html>
