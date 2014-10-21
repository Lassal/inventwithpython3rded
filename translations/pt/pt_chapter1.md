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
Importante! Se assegure de instalar Python 3, e não Python 2. Os programas neste livro usam Python 3 e você irá encontrar erros e você tentar rodar eles em Python2. Isto é tão importante que eu adicionei um desenho de pinguim na Figura 1-1 para te avisar que instalar Python 3 para você não perder esta mensagem.



Figure 1-1: An incongruous penguin tells you to install Python 3.
Figura 1-1: Um pinguim inconformado te avisa a instalar Python 3.

Starting IDLE
Iniciando o IDLE

IDLE stands for Interactive DeveLopment Environment. The development environment is like word processing software for writing Python programs. Starting IDLE is different on each operating system.
IDLE é a sigla do inglês Interactive DeveLopment Environment, que em português é Ambiente Interativo de Desenvolvimento. Este ambiente de desenvolvimento é um programa como um editor de textos para escrever programas em Python. Iniciar o IDLE é diferente em cada sistema operacional.

On Windows, click the Start button in the lower left corner, type “IDLE” and select IDLE (Python GUI).
No Windows, clique no botão Iniciar no canto inferior esquerdo da sua tela, e digite "IDLE" e selecione IDLE (Python GUI).


On Mac OS X, open the Finder window and click on Applications. Then click Python 3.4. Then click the IDLE icon.
No Mac OS X, abra a janela do Finder e clique em Aplicações, então clique em Python 3.4 e depois no icone do IDLE.

On Ubuntu or Linux, open a terminal window and then type “idle3”. You may also be able to click on Applications at the top of the screen. Then click Programming and IDLE 3.
No Ubuntu ou Linux, abra uma janela de terminal e então digite "idle3". Você pode também ser capaz de clicar em Aplicações no topo da tela e então selecionar Programação e IDLE 3.


Figure 1-2: The IDLE program’s interactive shell on Windows, OS X, and Ubuntu Linux.
Figura 1-2: O programa "shell" interativo IDLE no Windows, OS X, e Ubuntu Linux. 

The window that appears when you first run IDLE is the interactive shell. You can enter Python instructions into the interactive shell and Python will perform them. Python will display instruction results back in the interactive shell.
A janela que aparece quando você primeiro executa IDLE é um "shell" interativo. Um "shell" é um programa que permite que você digite comandos e estes sejam interpretados e executados. Você pode digitar seus comandos Python no shell interativo e eles seram executados pelo Python. E os resultados desta execução serão exibidos de volta neste shell (onde você digitou os comandos).

How to Use this Book
Como usar este livro

Most chapters in this book will begin with a sample run of the featured program. This sample run shows you what the program looks like when you run it. The user types in shown as bold print.
Maioria dos capítulos neste livro irão começar com um exemplo da execução do programa sendo apresentado. Este exemplo mostra como é o programa quando você executa ele. O código digitado pelo usuário está em negrito.

Type the code for the program into IDLE’s file editor yourself, rather than download it. You’ll remember programming better if you type in the code.
Apesar da tentação e facilidade de baixar o código e copiar e colar no editor do IDLE, digite o código você mesmo. Desta forma você irá lembrar e entender melhor o que esta programando. 

Line Numbers and Spaces
Número de linhas e spaços

When typing the source code, do not type the line numbers appear at the beginning of each line. For example, if you see this in the book:
Quando for digitar o código fonte, não digite os números que aparecem no inicio de cada linha. Por exemplo, se você vir isto no livro

9. number = random.randint(1, 20)
9. numero = random.randint(1, 20)

You do not need to type the “9.” on the left side, or the one space immediately following it. Just type it like this:
Você não precisa digitar o "9." no lado esquerdo ou o espaço imediatamente seguido a ele. Simplesmente digite isso desta forma:

number = random.randint(1, 20)
numero = random.randint(1, 20)

Those numbers are only so this book can refer to specific lines in the programs. They are not a part of the actual program.
Estes números existem para que o livro possa referenciar linhas específicas nos programas. Eles não são realmente parte do programa.

Aside from the line numbers, enter the code exactly as it appears. Notice that some of the lines of code are indented by four or eight spaces. Each character in IDLE is the same width. Count the number of spaces by counting the number of characters on the line above or below.
Tirando os números das linhas digite o código exatamente como ele aparece. Perceba que algumas linhas de código são indentadas por 4 ou 8 espaços. Cada character no IDLE tem a mesma largura. Conte o número de espaços contando o número de carácteres na linha acima ou abaixo.

For example, the indented spaces here are marked with a ▪ black square:
Por exemplo os spaços indentados aqui são marcados com um ▪ quadrado preto:

while guesses < 10:
▪▪▪▪if number == 42:
▪▪▪▪▪▪▪▪print('Hello')

while chances < 10:
▪▪▪▪if numero == 42:
▪▪▪▪▪▪▪▪print('Oi')

Text Wrapping in This Book
Quebra de texto neste livro

Some lines of code are too long to fit on one line on the page and will wrap around to the next line. Enter this code all on one line without pressing Enter. You can tell when a new line starts by looking at the line numbers on the left side of the code. For example, the code below has only two lines of code:
Algumas linhas de código são muito grandes para caber numa só linha na página e serão quebradas para a próxima linha. Quando for digitar, digite todo o código sem pressionar o "Enter". Você conseguirá dizer quando uma nova linha começa pelo número no inicio da linha. Por exemplo o código abaixo tem somente duas linhas de código:

1. print('This is the first line! xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
xxxxxxxxxxxx')
2. print('This is the second line, not the third line.')

1. print('Esta é a primeira linha! xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
xxxxxxxxxxxx')
2. print('Esta é a segunda linha, não a terceira.')

The first line wraps around and makes it look like three lines in total. That is only because this book’s pages aren’t wide enough to fit the first line on one line.
A primeira linha quebra e faz parecer como 3 linhas ao todo. Isto só acontece porque as páginas deste livro não são largas o suficiente para para caber a primeira linha numa linha da página.

Finding Help Online
Buscando ajuda online

This book’s website is at http://inventwithpython.com. You can find several resources related to this book there. Several links in this book use the invpy.com domain name for shortened URLs.
Este website deste livro esta em http://inventwithpython.com. Você pode encontrar diversos recursos relacionados a este livro lá. Vários links neste livro usam o dominio invpy.com para versões reduzidas das URLs.

The subreddit web site at http://reddit.com/r/inventwithpython is a great place to ask programming questions related to this book. Post general Python questions to the LearnProgramming and LearnPython subreddits at http://reddit.com/r/learnprogramming and http://reddit.com/r/learnpython, respectively.
O subreddit website em http://reddit.com/r/inventwithpython é um ótimo lugar para perguntar questões de programação relacionadas a este livro. Poste questões gerais sobre Python em LearnProgramming e LearnPython subreddits em http://reddit.com/r/learnprogramming e http://reddit.com/r/learnpython, respectivamente.

Also, email me your programming questions at al@inventwithpython.com.
Você pode também me enviar suas questões de programação em al@inventwithpython.com.

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

