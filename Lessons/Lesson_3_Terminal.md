# Lesson 3 - Terminal

## Index

* [*Install Cmder*](#install-cmder)
* [*Secure Shell*](#secure-shell)
* [*Source Control*](#source-control)
* [*Compile*](#compile)
* [*Execute*](#execute)

## Install Cmder

> Cmder is an excellent command line interface for Windows machines, people MacOS can use the built in Terminal program.

Download -> [Cmder](https://github.com/cmderdev/cmder/releases/download/v1.3.6/cmder_mini.zip)

Click on *Show in folder*.

<div class="videoWrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/r1VjkGYyRHE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe></div>

Right Click and then *Extract Here*.

<div class="videoWrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/epwpiUeL5xI" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe></div>

Open Application.

<div class="videoWrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/x6MhM5kNfYk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe></div>

## Secure Shell

> SSH or SecureShell is a application that allows you to remotely accesses other Linux computers. This allows people to share one single computer or work on another computer remotely.

Replace 'X' with user number and enter the command below. NOTE: This will only work in the Computer Labs during the camp!

``` bash
ssh UserX@10.185.1.169
```

Say *yes* if you get a prompt.

Enter password *1234*.

## Source Control

> GIT is a application that allows exchange of code and is used to log modification to files that are shared among multiple users. We only use it to download source code.

Enter the command below.

``` bash
git clone https://github.com/alexdantas/nSnake.git
```

## Compile

> Code on its own is just a bunch of text. It has to be translated so the machine can understand it. This process of translation is called compiling your code.

Enter the commands below.

``` bash
cd nSnake
make
```

## Execute

> At this point we have the code translated to what a machine can understand. But when does it start reading it? We have to tell it start reading the code and running the application. This process is called execution.

Enter the commands below.

``` bash
cd bin
./nsnake
```

** Here is a video showing this process: **

<div class="videoWrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/JpYJ_x3BnXg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe></div>
