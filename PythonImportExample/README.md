<<<<<<< HEAD
## PythonImportExample

This is the example package used in my blogpost [How Imports Work in Python](https://ivanocampo.com/?p=1994).

The post discusses:
* what happens when you import a python module
* some key terms associated with Python's import system, like `__init__.py` and `sys.path`
* some scenarios that might arise while working with imports
* creating your own package
* and relative vs absolute imports.

The code here is the final result that is achieved in the article.

### Contents
The file structure is:
```
PythonImportExampleProject/
    setup.py
    
    config related files (gitignore, LICENCE, etc.)
    pythonimportexample/
        __init__.py
        file1.py
        file2.py
        subpackage1/
            __init__.py
            file3.py
            file4.py
        subpackage2/
            __init__.py
            file5.py
            file6.py
```

Modules are imported in the following way:
* file1 into file2
* file3 into file4
* file3 into file5
* file6 into file2
* file2 into file6

Yup, the last one's a circular import.

### Usage
1. Clone this repo
2. Navigate to the PythonImportExample directory
3. Install this package

Simply execute:
```
$ git clone https://github.com/allitnils/BlogCode.git 
$ cd PythonImportExample
$ pip install -e .
```

You can find me [here](https://ivanocampo.com).
=======
## PythonImportExample

This is the example package used in my blogpost [How Imports Work in Python](https://ivanocampo.com/?p=1994).

The post discusses:
* what happens when you import a python module
* some key terms associated with Python's import system, like `__init__.py` and `sys.path`
* some scenarios that might arise while working with imports
* creating your own package
* and relative vs absolute imports.

The code here is the final result that is achieved in the article.

### Contents
The file structure is:
```
PythonImportExampleProject/
    setup.py
    
    config related files (gitignore, LICENCE, etc.)
    pythonimportexample/
        __init__.py
        file1.py
        file2.py
        subpackage1/
            __init__.py
            file3.py
            file4.py
        subpackage2/
            __init__.py
            file5.py
            file6.py
```

Modules are imported in the following way:
* file1 into file2
* file3 into file4
* file3 into file5
* file6 into file2
* file2 into file6

Yup, the last one's a circular import.

### Usage
1. Clone this repo
2. Navigate to the PythonImportExample directory
3. Install this package

Simply execute:
```
$ git clone https://github.com/allitnils/BlogCode.git 
$ cd PythonImportExample
$ pip install -e .
```

You can find me [here](https://ivanocampo.com).
>>>>>>> 5069d6c915e63a4c95a5f1c80fa9962d55628e36
