---
layout: post
title: Stories overview
published: true
---
# Storytelling Programming Language
COMP4036 Class Project

(Features and tools are subject to change)

Team members

Zuleinis Ramos: zuleinis.ramos@upr.edu 
Github: 

Bryan Otero: bryan.otero@upr.edu
Github: https://github.com/Bryan-otero

Javier Flores: javier.flores6@upr.edu
Github: https://github.com/JaviFlowers

Motivation

  Searching creativity, finding inspiration and using your imagination for making art is hard enough, and translating it into works of technology makes it even harder. The Storytelling Language will be created to solve this problem and to ease the path to connect art and technology for programmers in the fields of storytelling. The language will provide the tools that storytellers need to serve as a vessel for the creative process while reducing the need to focus on more analytical and structural aspects. For this, the language will provide a structure to automatically piece together a format that most suits the programmer’s work. Additionally, the language will provide all the help the storyteller needs to turn the story into data and storing it. This language is suited for programmers in the field of game design and film.
  
Our reasoning behind making this storytelling programming language is because we are all interested in the same working fields, that being game and/or web development. For this project we chose as our main programming language Python. We are students from the computer science department, and in UPRM the main language taught to us is C++. After digging for information we agreed upon using Python 3 as our main language not only because It is arguably easier to create a language using it but because it is a completely new language for us and it is very popular in the industry so we would like to learn more about it even if its not directly taught to us at the moment.

Example programs

- Interactive stories (games, books.. “gamebooks”):
  Allows the user to participate in the story by making choices that impact the path. The programmer will be able to write in choices for this user and scenarios in the story. The language will provide this and will organize the scenarios as determined by the programmer.
- Story elements scanner: 
  Detects story elements from a file and stores them. Additionally has the ability to extract specific story details and scenarios from other files, effectively having the ability to merge more than one story together.
- Story formatter:
  Generates a file with a formatted story based on it’s type. The story types can be but are not limited to game story scripts, screenplays, short stories and novels.
  
Language Features

- Variables
- Functions
- Non-primitive data structures
- User generated data structures
- Story metadata 
- Document formatting (TXT, HTML, PDF)

Implementation requirements and tools

- Python 3
  is an interpreted, object-oriented, high-level programming language with dynamic semantics.
- Pandoc
  is a Haskell library for converting from one markup format to another, and a command-line tool that uses this library.
- Sly
  is a parsing tool that helps us figure out why our parser is not working and tell the user why their code is not valid.
- Ebooklib
  is a Python library for managing EPUB2/EPUB3 and Kindle files. It’s capable of reading and writing EPUB files programmatically.

How to install requirements and tools 

- Sly
  1. Open the CMD Terminal and copy/type in pip install sly (requires the use of Python 3.6 or greater) and press enter as seen via the link https://pypi.org/project/sly/
  2. After Sly is installed, to import the sly Lexer library to your code at the top copy/type: 
  from sly import Lexer
  3. Below from sly import Lexer, to import sly Parser copy/type
  from sly import Parser

- EbookLib
  1. In order to run the epub file, install Adobe Digital Editions 4.5.11 by following the instructions via the link https://www.adobe.com/la/solutions/ebook/digital-editions/download.html
  2. Open the CMD Terminal and copy/type pip install EbookLib and press enter as seen via the link https://pypi.org/project/EbookLib/.
  3. After EbookLib is installed, to import into the code copy/type
    from ebooklib import epub

How to use 

To assign a value to each of the Story variables such as Title the programmer must write The name of the variable followed by "=" and finally the value. An example can be TITLE = "The Iron Giant".

This process must be done to all Story variables in order to be exported which are:

TITLE
AUTH
LANG
BODY
SETTING
CHARACTER
ID

After all of the Story variables are assigned values, then the programmer is able to export the book by simply typing EXPORT on the code line.

By doing this a seperate file will be created. To open it search for the epub file in the file explorer and open it using Adobe Digital Edition.
