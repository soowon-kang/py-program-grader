# py-program-grader
---
Python program source grader

---

## Requirement

The grading.py can only grade a file named as solution.py, which has main() function.
You have to create all input and sample solution files before you grade solution.py.

The names of input files should be 'input*.txt'. (* is a number.)
The names of soluiton files should be 'sol*.txt'. (* is a number.)
The number should be gradually increasing started by 0.


## Excution example

    $ cat solution.py
    def main():
        a = raw_input()
        b = input()
        print type(a), a
        print type(b), b
    
    $ cat input0.txt
    417
    115

    $ python grading.py
    How many input files? 1

    $ cat output0.txt
    <type 'str'> 417
    <type 'int'> 115
    EXCUTION TIME: 0.000118017196655


