# Lesson 4 - Hello World

## Index

* [*Follow Instructions*](#follow-instructions)
* [*C Hello World*](#c-hello-world)
* [*Python Hello World*](#python-hello-world)

## Follow Instructions

> Please use previous knowledge and this instructional to get to the right setup for this lab session.

Open Cmder

Enter the following commands and remember to replace 'X' with your assigned user number:

``` bash
ssh UserX@10.185.1.169
yes
1234
git clone https://github.com/AnirudhPal/PALS_C_Hello_World.git
cd PALS_C_Hello_World
make
./hello
```

## C Hello World

> A Hello World program is generally the simplest and first program a programmer writes in a new programming language. We are going to write such a program for the programming language C.

Enter the command:

``` bash
vim hello.c
```

Use arrow keys to get to line 7.

Press *i*.

Type *printf("Hello World!!");*

Press *ESC*.

Type *:wq*.

Enter the following commands:

``` bash
make
./hello
```

## Python Hello World

> We will do the same for the programming language Python.

Enter the command:

``` bash
python
```

Type *print("Hello World!!")*.

### Here is a video showing this process:

<div class="videoWrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/_NAz2m07jjY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe></div>
