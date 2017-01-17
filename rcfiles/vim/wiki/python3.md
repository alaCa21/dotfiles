# dicas Sobre python3

``` markdown
File:		 Python3.md
Created:	 sáb 07 jan 2017 07:29:27 BRT
Last Change: ter 10 jan 2017 15:50:19 BRT
Author:		 Sergio Araujo
Site:		 http://vivaotux.blogspot.com
e-mail:      <voyeg3r ✉ gmail.com>
Twitter:	 @voyeg3r
Github:      https://github.com/voyeg3r
```

#### curso completo no youtube

* [canal ignorancia zero](https://www.youtube.com/channel/UCmjj41YfcaCpZIkU-oqVIIw)
* [python course in English](https://www.youtube.com/watch?v=R6wQmWMDiB4)
* [aula 001](https://www.youtube.com/watch?v=sC6mqcLSkZo&index=2&list=PLfCKf0-awunOu2WyLe2pSD2fXUo795xRe)
* [another course](https://www.youtube.com/watch?v=f6ji-QcOo_U)
* [another one](https://www.youtube.com/watch?v=QSzqiGeyU5s)
* [Programming Foundations with Python](https://www.youtube.com/watch?v=X0FoelOIZM0&list=PLAwxTw4SYaPnYajEbZvqtcVWQ6XGhvtOW)
* [Zero to Hero with Python Tutorial FULL Easy](https://www.youtube.com/watch?v=TV9tSHFAFjg)
* [livro think python](https://upload.wikimedia.org/wikipedia/commons/1/1b/Think_Python.pdf)
* [byte of python](http://files.swaroopch.com/python/byte_of_python.pdf)

### um desafio interessante baseado em python2
**Learn Python Through Public Data Hacking**

* [PyCon 2013 Video](http://pyvideo.org/pycon-us-2013/learn-python-through-public-data-hacking.html)
* http://www.dabeaz.com/pydata/
* https://www.youtube.com/watch?v=RrPZza_vZ3w

#### to be able to import turtle in python
[read on this link](https://opentechschool.github.io/python-beginners/en/simple_drawing.html)

    sudo pacman -S community/python-pmw

#### assigning a range or printing

    To print a list [1, 3, 5, 7, 9, 11]

    print(list(range(1,12,2)))

#### Converting python2 to python3

   2to3 python2script.py

   to write changes use -w

   2to3 -w python2script.py

#### Access to the clipboard

    import pyperclip

#### print clipboard contente

``` python
pyperclip.paste()
var = pyperclip.paste()
print(var)
```

#### random numbers

``` python
iport random
random_num=random.randrange(0,100)

while(random_num != 15):
    print(random_num)
    random_num = random_num.range(0,100)
```

#### addnumbers function

``` python
def addNumber(fNum, lNum):
    sumNum = fNum + lNum
    return sumNum

print(addNumber(1,4))
```

#### Getting user input

``` python
import sys
print('What is your name?')
name = sys.stadin.readline()
print('Hello', name)
```