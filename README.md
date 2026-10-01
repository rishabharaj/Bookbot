# BookBot

BookBot is a Python-based command-line tool designed to analyze text files and documents. It generates statistical reports including total word count and detailed character frequency analysis, sorted from most frequent to least frequent.

---

## Features

- **Word Count**: Calculates the total number of words in a given document.
- **Character Frequency Analysis**: Counts the occurrences of each alphabetical character (case-insensitive).
- **Sorted Terminal Reports**: Formats and prints results sorted in descending order of frequency for clean, readable output.
- **CLI Arguments Support**: Easily specify any text file path directly from the command line.

---

## Project Structure

```
Bookbot/
├── books/
│   ├── frankenstein.txt       # Mary Shelley's Frankenstein
│   ├── mobydick.txt           # Herman Melville's Moby Dick
│   └── prideandprejudice.txt  # Jane Austen's Pride and Prejudice
├── main.py                    # Application entry point and report generation
├── stats.py                   # Text analysis functions (word count, character counts, sorting)
└── README.md                  # Project documentation
```

---

## Getting Started

### Prerequisites

- Python 3.8+ installed on your system.

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/rishabharaj/Bookbot.git
cd Bookbot
```

---

## Usage

Run the program with Python 3, passing the relative or absolute path of the book file you want to analyze:

```bash
python3 main.py <path_to_book>
```

### Examples

Analyze *Frankenstein*:

```bash
python3 main.py books/frankenstein.txt
```

Analyze *Moby Dick*:

```bash
python3 main.py books/mobydick.txt
```

Analyze *Pride and Prejudice*:

```bash
python3 main.py books/prideandprejudice.txt
```

---

## Example Output

Running `python3 main.py books/frankenstein.txt` produces:

```text
============ BOOKBOT ============
Analyzing book found at books/frankenstein.txt...
----------- Word Count ----------
Found 75767 total words
--------- Character Count -------
e: 44538
t: 29493
a: 25894
o: 24494
i: 23927
n: 23643
s: 20360
r: 20079
h: 19176
d: 16318
l: 12306
m: 10206
u: 10111
c: 9011
f: 8451
y: 7756
w: 7450
p: 5952
g: 5795
b: 4868
v: 3737
k: 1661
x: 691
j: 497
q: 325
z: 235
============= END ===============
```

---

## Author

- **Rishabh** - [@rishabharaj](https://github.com/rishabharaj)
