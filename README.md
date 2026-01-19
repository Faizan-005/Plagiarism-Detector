# Plagiarism-Detector
First Repository
<br>
<h1>📄 Plagiarism Detection System (C++)</h1>

<p>
The <strong>Plagiarism Detection System</strong> is a console-based application developed in <strong>C++</strong> that analyzes textual similarity between a reference file and a target file. 
It uses <strong>tokenization</strong>, <strong>hashing</strong>, and <strong>K-gram matching</strong> techniques to detect and highlight plagiarized content efficiently.
</p>

<hr>

<h2>🎯 Project Objectives</h2>
<ul>
  <li>Detect plagiarism between two text files</li>
  <li>Identify matching sequences of words (K-grams)</li>
  <li>Highlight plagiarized sections in the target text</li>
  <li>Calculate plagiarism percentage accurately</li>
  <li>Provide a user-friendly menu-driven interface</li>
</ul>

<hr>

<h2>⚙️ Key Features</h2>
<ul>
  <li>Token-based text comparison</li>
  <li>K-gram hashing technique for efficient matching</li>
  <li>Multiple plagiarism sensitivity levels</li>
  <li>Colored console output for better readability</li>
  <li>Displays matched phrases and plagiarism percentage</li>
  <li>Menu-driven system for easy interaction</li>
</ul>

<hr>

<h2>🧠 Working Principle</h2>
<p>
The system reads two text files:
</p>
<ul>
  <li><strong>Reference File</strong> – Original content</li>
  <li><strong>Target File</strong> – Content to be checked</li>
</ul>

<p>
Both files are tokenized into words. Using a <strong>K-gram approach</strong>, sequences of <code>K</code> consecutive tokens are hashed and compared. 
If hashes match, the corresponding section is marked as plagiarized. The final plagiarism percentage is calculated based on matched tokens.
</p>

<hr>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li><strong>Language:</strong> C++</li>
  <li><strong>Concepts:</strong> Hashing, File Handling, STL (Vectors, Sets, Maps)</li>
  <li><strong>Algorithm:</strong> Rolling Hash / K-Gram Matching</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<pre>
PlagarismDetector.cpp   // Main source file
</pre>

<hr>

<h2>▶️ How to Run</h2>
<ol>
  <li>Compile the program using a C++ compiler:</li>
</ol>

<pre>
g++ PlagarismDetector.cpp -o PlagiarismDetector
</pre>

<ol start="2">
  <li>Run the executable:</li>
</ol>

<pre>
./PlagiarismDetector
</pre>

<ol start="3">
  <li>Follow the on-screen menu to:</li>
</ol>

<ul>
  <li>Load reference and target files</li>
  <li>Select K-gram size</li>
  <li>Choose plagiarism sensitivity level</li>
  <li>View results and matched content</li>
</ul>

<hr>

<h2>📊 Output</h2>
<ul>
  <li>Plagiarism percentage</li>
  <li>Highlighted plagiarized words</li>
  <li>Matched phrases between files</li>
  <li>Colored output for better visualization</li>
</ul>

<hr>

<h2>🚀 Future Improvements</h2>
<ul>
  <li>GUI-based interface</li>
  <li>Support for multiple file formats</li>
  <li>Semantic similarity detection</li>
  <li>Report export (PDF / TXT)</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>
<p>
Developed as an academic and learning project to understand <strong>text similarity analysis</strong>, <strong>hashing techniques</strong>, and <strong>file processing in C++</strong>.
</p>

<hr>

<h2>📜 License</h2>
<p>
This project is open for educational use and learning purposes.
</p>

