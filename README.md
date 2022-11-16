# Scratch project And  basic programming concepts

https://scratch.mit.edu/projects/727993094/

# What did i learn?

## Binary numbers

they are nothing more than transistors on(with energy flowing)/off (without)
Each binary digit is also called a bit.
Unlike "normal" numbers binaries numbers have powers of two

- 2^2 2^1 2^0 (4 2 1)</li>
- 001 = 1
- 101 = 5
- 111 = 7

Most computers use 8 bits (2^8  or 256 different values (including zero)) at a time also known as <strong>Byte</strong>, like 00000011 for the number 3.

## Representing letters with binary number

The letter “A”, for example, is the number 65, and “B” is 66, and so on. In binary, the letter “A” is the pattern 01000001. By using context, like the file format, different programs can interpret and display the same bits as numbers or text.

The standard mapping, ASCII, also includes lowercase letters and punctuation.
<img src="https://www.alpharithms.com/s3/assets/img/ascii-chart/ascii-table-alpharithms-scaled.jpg" alt="ASCII table" width="800" height="400"> 

## How can a computer have this mapping from numbers to letters, but still support numbers?
<p>Different file formats, Excel versus Photoshop versus Google Docs or the like, we shall interpret any patterns of zeros and ones as being maybe numbers for Excel, maybe letters in, like, a text messaging program or Google Docs, or maybe even colors of the rainbow in something like Photoshop and more. So it's context dependent.</p>

## Representing Images and videos
With bits, we can map numbers to colors as well. There are many different systems to represent colors, but a common one is RGB, which represents colors by indicating the amount of red, green, and blue within each color, each number might be 8 bits, with 256 possible values.

rgb(255,255,255)

Videos are sequences of many images, changing multiple times a second to give us the appearance of motion,
Music can be represented with bits, too. MIDI is one such format which represents music with numbers for each of the notes and their duration and volume.

## Algorithm
Algorithm is just step-by-step instructions for solving some problem incarnated in the world of computers by software.

For example openning a book and start to search for a name page by page

## Pseudocode

The representation of an algorithm in human language such as english or portuguese

  ```
  1  Pick up phone book
  2  Open to middle of phone book
  3  Look at page
  4  If person is on page
  5      Call person
  6  Else if person is earlier in book
  7      Open to middle of left half of book
  8      Go back to line 3
  9  Else if person is later in book
  10     Open to middle of right half of book
  11     Go back to line 3
  12 Else
  13     Quit
  
```

<strong>Functions</strong> are actions or verbs that solve some smaller problem

 - Pick
 - Open
 - Look

<strong>Conditionals</strong> are things that you do conditionally based on the answer to some question.


- If
- Else if
- Else

That question being a <strong>boolean expression</strong> in other words true or false


- person is on page? true or false
- person is earlier in book? true or false 
Loops a cycle or directive that tells us to do something again and again

Go back to line 3

