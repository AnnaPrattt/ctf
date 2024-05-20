## Description
Lydia loves Jane Austen. In fact, her favorite book is Pride and Prejudice. She loves the book so much that she decided to use only references to the book to communicate with her friends when passing secret notes. Unfortunately Lydia's friends don't understand her secret code -- could you help them out and identify the secret message? (Wrap the secret message in byuctf{} in all lowercase and no spaces, for example byuctf{thisisthesecretmessage}

1.1.1 8.9.8 10.2.11 4.14.28  61.2.4  47.10.3  23.7.37  41.12.3 17.6.10 1.1.21

# Writeup

This is a standard cipher in which the numbers reference specific letters in a book. The book here is obviously Pride and Prejudice. The book is in the public domain so it can be found online. 

The numbers stand for CHAPTER.PARAGRAPH.LETTER. Note that the character references only alphabetic characters, so skip over any punctuation and spaces. Although it is certain that formatting may differ between different editions online, when I searched Google for "pride and prejudice book online", these were the top results and they all have similar formatting. Any of these sites would work for solve the cipher.

* https://www.janeausten.org/pride-and-prejudice/pride-and-prejudice-online.php
* https://www.fulltextarchive.com/book/pride-and-prejudice/
* https://www.gutenberg.org/files/1342/1342-h/1342-h.htm
* https://giove.isti.cnr.it/demo/eread/Libri/joy/Pride.pdf
* https://www.planetebook.com/free-ebooks/pride-and-prejudice.pdf

Below is a direct mapping of each section to the letter represented:

1.1.1 (i) <br>
8.9.8 (l) <br>
10.2.11 (o) <br>
4.14.28 (v) <br>
61.2.4 (e) <br>
47.10.3 (d) <br>
23.7.37 (a) <br>
41.12.3 (r) <br>
17.6.10 (c) <br>
1.1.21 (y) <br>

**Flag -** ```byuctf(ilovedarcy)```
