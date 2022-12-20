# Exception

Example:
``` python
#!/usr/bin/python
def KelvinToFahrenheit(Temperature):
    assert (Temperature >= 0),"Colder than absolute zero!"
    return ((Temperature-273)*1.8)+32
print (KelvinToFahrenheit(273))
print (int(KelvinToFahrenheit(505.78)))
print (KelvinToFahrenheit(-5))
```
Output:
![exception](https://github.com/HizkiaVin/praktikum11/blob/main/screenshot/Screenshot%202022-12-20%20100103.png?raw=true)

> **What is Exception?**
\
An exception is an event, which occurs during the execution of a program that disrupts the normal flow of the program's instructions. In general, when a Python script encounters a
situation that it cannot cope with, it raises an exception. exception. An exception is a Python object that represents an error.
When a Python script raises an exception, it must either handle the exception immediately otherwise it terminates and quits.
>

>**Handling Exception**
\
If you have some suspicious code that may raise an exception, you can defend your program program by placing the suspicious  code in a **try**: block. After the try: block, include an **except**: statement, followed by a block of code which handles the problem as elegantly as possible.