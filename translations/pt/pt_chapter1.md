    Chapter 1
    INSTALLING PYTHON
    Capítulo 1
    INSTALANDO PYTHON

Topics Covered In This Chapter:
Tópicos cobertos nestes capítulo:

•   Downloading and installing the Python interpreter
•   IDLE’s interactive shell
•   How to use this book
•   The book’s website at http://inventwithpython.com
•   Baixar e instalar o interpretador Python
•   Execução do IDLE´s no modo interativo
•   Como usar este livro
•   O website do livro em http://inventwithpython.com


Hello! This book teaches you how to program by making video games. Once you learn how the games in this book work, you’ll be able to create your own games. All you’ll need is a computer, some software called the Python interpreter, and this book. The Python interpreter is free to download from the Internet.
Oi pessoal! Este livro ensina você a programar a partir de vários jogos de computador. Uma vez que você aprender como os jogos nestes livro funcionam você será capaz de criar os seus próprios jogos. Tudo o que você vai precisar é um computador, um programa chama interpretador Python, e este livro. O interpretador Python é gratuíto e pode ser baixado da internet.

When I was a kid, a book like this one taught me how to write my first programs and games. It was fun and easy. Now as an adult, I still have fun programming and I get paid for it. But even if you don’t become a computer programmer when you grow up, programming is a useful and fun skill to have.
Quando eu era um garoto, um livro como este me ensinou como escrever meus primeiros programas e jogos. Era divertido e fácil. Agora, como um adulto, I ainda me divirto programando e agora recebo por isso. Mas mesmo se você não se tornar um programador quando crescer, programação é um conhecimento muito util (e divertido) de se ter.

Computers are incredible machines, and learning to program them is easy. If you can read this book, you can program a computer. A computer program is a bunch of instructions that the computer can understand, just like a storybook is a bunch of sentences understood by the reader. Video games are nothing but computer programs, so they are also made up of instructions.
Computadores são máquinas incríveis, e aprender a programa-los é fácil. Se você consegue ler este livro você consegue programar um computador. Um programa de computador é um monte de instruções que um computador consegue entender, da mesma forma que um livro de histórias são um monte de texto que é entendido por quem lê. Jogos de computador (video games) nada mais são que programas de computador, eles também são feitos de um monte de instruções para computador.

To instruct a computer, you write a program in a language the computer understands. This book teaches a programming language named Python. There are many different programming languages including BASIC, Java, JavaScript, PHP, and C++.
Para instruir um computador você escreve um programa numa linguagem que o computador entenda. Este livro ensina uma linguagem chamada Python. Há muitas linguagens de programa diferentes incluindo BASIC, Java, Javascript, PHP e C++.

When I was a kid, BASIC was a common first language to learn. However, new programming languages such as Python have been invented since then. Python is even easier to learn than BASIC! But it’s still a serious programming language used by professional programmers. Many adults use Python in their work and when programming for fun.
Quando eu era criança era comum BASIC ser a primeira linguagem de escolha pra se aprender. Entretanto novas linguagens de programação foram criadas desde então. Python é ainda mais fácil de aprender que BASIC! Mas é também uma linguagem de programação séria usada por programadores profissionais em empresas e institutos de pesquisa. Muitos adultos usam Python em seu trabalho e quando programam para se divertir.

The games you’ll create from this book seem simple compared to the games for the Xbox, Playstation, or Wii. These games don’t have fancy graphics because they’re meant to teach coding basics. They’re purposely simple so you can focus on learning to program. And games don’t have to be complicated to be fun.
Os jogos que você ira criar a partir deste livro parecem simples comparados com jogos para Xbox, Playstation ou Wii. Estes jogos não possuem graficos incríveis porque eles tem o proposito de ensinar a base de programação. Eles são simples de propósito assim você pode focar em aprender a programar. Outro ponto é que os jogos não precisam ser complicados para serem divertidos.

Downloading and Installing Python
Baixe e instale Python

You’ll need to install software called the Python interpreter. The interpreter program understands the instructions you’ll write in the Python language. I’ll just refer to “the Python interpreter software” as “Python” from now on.
Você irá precisar instalar um software chamado interpretador Python. O interpretador é um programa que entende as instruções que você irá escrever na linguagem Python. Daqui pra frente eu vou chamar "o interpretador de programas em Python" de "Python" no resto do livro.

Download Python 3.4 or a later version from the official Python website, http://www.python.org. Download the 32-bit version of Python for your operating system, even if you have a 64-bit computer. The Pygame module used later in this book currently runs only on 32-bit Python.
Baixe Python 3.4 ou uma versão superior do site official do Python em http://www.python.org. O site esta todo em inglês mas basta você procurar pelo menu Downloads e baixar a versão para o seu sistema operacional. IMPORTANTE baixe a versão 32-bit mesmo se você tiver um computador 64-bits. O módulo Pygame usado no fim do livro roda somente em Python 32-bit. Para quem tiver sistema operacional Windows procure pelo "Windows x86 MSI installer" que é a versão 32-bit do instalador para Windows.

Important Note! Be sure to install Python 3, and not Python 2. The programs in this book use Python 3, and you’ll get errors if you try to run them with Python 2. It is so important, I’ve added a cartoon penguin in Figure 1-1 to tell you to install Python 3 so you do not miss this message.



Figure 1-1: An incongruous penguin tells you to install Python 3.

Starting IDLE

IDLE stands for Interactive DeveLopment Environment. The development environment is like word processing software for writing Python programs. Starting IDLE is different on each operating system.

On Windows, click the Start button in the lower left corner, type “IDLE” and select IDLE (Python GUI).

On Mac OS X, open the Finder window and click on Applications. Then click Python 3.4. Then click the IDLE icon.

On Ubuntu or Linux, open a terminal window and then type “idle3”. You may also be able to click on Applications at the top of the screen. Then click Programming and IDLE 3.



Figure 1-2: The IDLE program’s interactive shell on Windows, OS X, and Ubuntu Linux.

The window that appears when you first run IDLE is the interactive shell. You can enter Python instructions into the interactive shell and Python will perform them. Python will display instruction results back in the interactive shell.

How to Use this Book

Most chapters in this book will begin with a sample run of the featured program. This sample run shows you what the program looks like when you run it. The user types in shown as bold print.

Type the code for the program into IDLE’s file editor yourself, rather than download it. You’ll remember programming better if you type in the code.

Line Numbers and Spaces

When typing the source code, do not type the line numbers appear at the beginning of each line. For example, if you see this in the book:

9. number = random.randint(1, 20)

You do not need to type the “9.” on the left side, or the one space immediately following it. Just type it like this:

number = random.randint(1, 20)

Those numbers are only so this book can refer to specific lines in the programs. They are not a part of the actual program.

Aside from the line numbers, enter the code exactly as it appears. Notice that some of the lines of code are indented by four or eight spaces. Each character in IDLE is the same width. Count the number of spaces by counting the number of characters on the line above or below.

For example, the indented spaces here are marked with a ▪ black square:

while guesses < 10:
▪▪▪▪if number == 42:
▪▪▪▪▪▪▪▪print('Hello')

Text Wrapping in This Book

Some lines of code are too long to fit on one line on the page and will wrap around to the next line. Enter this code all on one line without pressing Enter. You can tell when a new line starts by looking at the line numbers on the left side of the code. For example, the code below has only two lines of code:

1. print('This is the first line! xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
xxxxxxxxxxxx')
2. print('This is the second line, not the third line.')

The first line wraps around and makes it look like three lines in total. That is only because this book’s pages aren’t wide enough to fit the first line on one line.

Finding Help Online

This book’s website is at http://inventwithpython.com. You can find several resources related to this book there. Several links in this book use the invpy.com domain name for shortened URLs.

The subreddit web site at http://reddit.com/r/inventwithpython is a great place to ask programming questions related to this book. Post general Python questions to the LearnProgramming and LearnPython subreddits at http://reddit.com/r/learnprogramming and http://reddit.com/r/learnpython, respectively.

Also, email me your programming questions at al@inventwithpython.com.

Keep in mind there are smart ways to ask programming questions that help others help you. Be sure to read the Frequently Asked Questions sections these websites have about the proper way to post questions. When asking programming questions, do the following:

•   If you are typing out the programs in this book but getting an error, first check for typos with the online diff tool at http://invpy.com/diff. Copy and paste your code into the diff tool to find any differences from the book’s code in your program.
•   Explain what you are trying to do when you explain the error. This will let your helper know if you are on the wrong path entirely.
•   Copy and paste the entire error message and your code.
•   Search the Web to see whether someone else has already asked (and answered) your question.
•   Explain what you’ve already tried to do to solve your problem. This tells people you’ve already put in some work to try to figure things out on your own.
•   Be polite. Don’t demand help or pressure your helpers to respond quickly.

Tracing the Programs Online

Tracing a program means to step through the code one line at a time, in the same way a computer would execute it. Visit http://invpy.com/traces to see a trace through of each program in this book. The web page has notes and helpful reminders at each step of the trace to explain what the program is doing, so it can help you better understand why these programs work the way they do.

Summary

This chapter has helped you get started with the Python software by showing you the http://python.org website where you can download it free. After installing and starting the Python IDLE software, you’ll be ready to learn programming starting in the next chapter.

This book’s website at http://inventwithpython.com has more information on each of the chapters, including an online tracing website and diff tool can help you understand the programs in this book.

