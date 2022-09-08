# Python 



## 1. Tab or space

in python (PEP-008) it's recommended to use space than tab, but we can still use tabs. "if it's using space type 4 spaces per indentation level.
In the end about tabs and space we must consitent chosing indentaion type

SRC: https://stackoverflow.com/questions/120926/why-does-python-pep-8-strongly-recommend-spaces-over-tabs-for-indentation#:~:text=The%20answer%20to%20the%20question,strongly%20recommend%20spaces%20over%20tabs.&text=PEP%2D8%20says%20'Use%204,this%20is%20the%20standard%20recommendation.

## 2. Expression, and Statement

expression adalah bagian pada python yang memiliki fungsi untuk meghasilkan value, sedangkan statement adalah bagian yang akan menggeloalah value tersebut, atau bertindak sebagai aksi. 

```
# Some example

"yes" + " this
x + 6
if a==3 else 2
	a or b
	2 and 3
	lambda x:x**2
```

- Statement - adalah bagian yang mengerjekan sesuatu
- Expression - adalah bagian yang menghasilkan nilai 

## 3. Python and Namespaces

namespace adalah kelompok nama dan juga memiliki fungsi mereka sendiri. 
Secara mudah kita bisa bayangkan namespace adalah sebuah kamus, yang dimana kata kunci adalah nama object, dan value adalah object itu sendiri.

Beberapa type namespace pada python:
1. Built-in, adalah namespace yang sudah ada dari awal pada python. Contohnya `True, False, int, str`. Cara untuk mengetahui Built-in namespace adalah `dir(__builtins__)`

2. Global namespace, adalah namespace yang berhasil kita buat dan bisa dipakai secara global / keseluruhan dalam code kita.

3. Local Namespaces, adalah namespace yang hanya bisa dipakai didalam scope tersebut saja, sebagai contoh: variabel didalam function, hanya bisa diakses didalam function tersebut saja.


SRC: https://docs.python.org/3/tutorial/classes.html
    https://realpython.com/python-namespaces-scope/#:~:text=the%20next%20level.-,Namespaces%20in%20Python,values%20are%20the%20objects%20themselves.

