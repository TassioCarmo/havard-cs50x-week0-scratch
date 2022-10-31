<h1>Scratch project using basic programming concepts</h1> 
https://scratch.mit.edu/projects/727993094/

<h1>What did i learn?</h1>

<h2>Binary numbers</h2>
<p>they are nothing more than transistors on(with energy flowing)/off(without</p>
<p>Each binary digit is also called a bit.</p>
<p>Unlike "normal" numbers binaries numbers have powers of two</p>
<ul>
  <li>2^2 2^1 2^0 (4 2 1)</li>
  <li>001 = 1</li>
  <li>101 = 5</li>
  <li>111 = 7</li>
</ul>
<p>Most computers use 8 bits (2^8  or 256 different values (including zero)) at a time also known as <Bold>Byte</Bold>, like 00000011 for the number 3.</p>

<h2>Representing letters with binary numbers</h2>
<p>The letter “A”, for example, is the number 65, and “B” is 66, and so on. In binary, the letter “A” is the pattern 01000001. By using context, like the file format, different programs can interpret and display the same bits as numbers or text.</p>
<p>The standard mapping, ASCII, also includes lowercase letters and punctuation.</p>
<img src="https://www.alpharithms.com/s3/assets/img/ascii-chart/ascii-table-alpharithms-scaled.jpg" alt="ASCII table" width="800" height="400"> 

<h4>How can a computer have this mapping from numbers to letters, but still support numbers?</h4>
<p>Different file formats, Excel versus Photoshop versus Google Docs or the like, we shall interpret any patterns of zeros and ones as being maybe numbers for Excel, maybe letters in, like, a text messaging program or Google Docs, or maybe even colors of the rainbow in something like Photoshop and more. So it's context dependent.</p>

<h2>Representing Images and videos</h2>
<p>With bits, we can map numbers to colors as well. There are many different systems to represent colors, but a common one is RGB, which represents colors by indicating the amount of red, green, and blue within each color, each number might be 8 bits, with 256 possible values.</p>

<p>rgb(255,255,255)</p>

<p>Videos are sequences of many images, changing multiple times a second to give us the appearance of motion,</p>
<p>Music can be represented with bits, too. MIDI is one such format which represents music with numbers for each of the notes and their duration and volume.</p>

<h2>Algorithm</h2>
<p>Algorithm is just step-by-step instructions for solving some problem incarnated in the world of computers by software.</p>

<p>For example openning a book and start to search for a name page by page</p>

<h2>Pseudocode</h2>

<p>The representation of an algorithm in human language such as english or portuguese</p>
  ```
  1  Pick up phone book </br>
  2  Open to middle of phone book</br>
  3  Look at page</br>
  4  If person is on page</br>
  5      Call person</br>
  6  Else if person is earlier in book</br>
  7      Open to middle of left half of book</br>
  8      Go back to line 3</br>
  9  Else if person is later in book</br>
  10     Open to middle of right half of book</br>
  11     Go back to line 3</br>
  12 Else
  13     Quit
```

<p>Functions are actions or verbs that solve some smaller problem</p>
<ul>
  <li>Pick</li>
  <li>Open</li>
  <li>Look</li>
</ul>

<p>Conditionals are things that you do conditionally based on the answer to some question. true or false</p>

<ul>
  <li>If</li>
  <li>Else if</li>
  <li>Else</li>
</ul>
