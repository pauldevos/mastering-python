# mastering-python

### Books
-----




### Writing Good Python Modules - Some Essential Python Libraries
- [attr](https://attrs.readthedocs.io/en/stable/)
  - [attr - The One Python Library Everyone Needs](https://glyph.twistedmatrix.com/2016/08/attrs.html)





### OOP
- [A Byte of Python](https://python.swaroopch.com/oop.html)
- [The Python Tutorial - Classes](https://docs.python.org/3/tutorial/classes.html)
- [Object-Oriented Programming (OOP) in Python 3](https://realpython.com/python3-object-oriented-programming/)
- [Python 101 - Object Oriented Programming - Part 1](https://medium.com/the-renaissance-developer/python-101-object-oriented-programming-part-1-7d5d06833f26)
- [Improve Your Python: Python Classes and Object Oriented Programming](https://jeffknupp.com/blog/2014/06/18/improve-your-python-python-classes-and-object-oriented-programming/)
- [Raymond Hettinger - Python's Class Development Toolkit](https://www.youtube.com/watch?v=HTLu2DFOdTg)
- [OOP - Trying To Design A Good Class Structure)](https://stackoverflow.com/questions/39922553/oop-trying-to-design-a-good-class-structure)



### Virtual Environments


#### Creating Your First Project & Virtual Environment

```
# Create a directory and enter into it
mkdir myproject && cd myproject

# create a python env
pyvenv venv

# Put the venv in your .gitignore:
git init
echo 'venv' > .gitignore
```
Doing this keeps your virtual environment out of source control (Git).
```
# Activate the environment:
source venv/bin/activate

# Install packages
pip install requests bs4

# Freeze the requirements:
pip freeze > requirements.txt

# Check requirements.txt into source control:
git add requirements.txt
```
