# Ultimate Python study guide

![](https://img.shields.io/circleci/build/github/huangsam/ultimate-python)
![](https://img.shields.io/github/followers/huangsam)
![](https://img.shields.io/github/stars/huangsam/ultimate-python)
![](https://img.shields.io/github/license/huangsam/ultimate-python)

Ultimate Python study guide for newcomers and professionals alike. :snake: :snake: :snake:

```python
print("Ultimate Python study guide")
```

## Motivation :mortar_board:

I created a GitHub repo to share what I've learned about [core Python](https://www.python.org/)
over the past 5+ years of using it as a college graduate, an employee at
large-scale companies and as an open-source contributor of repositories like
[Celery](https://github.com/celery/celery) and
[Full Stack Python](https://github.com/mattmakai/fullstackpython.com).
I look forward to seeing more people learn Python and pursue their passions
through it.

## Goals :trophy:

Here are the primary goals of creating this guide:

**Serve as a resource** for Python newcomers who prefer to learn hands-on.
This repository has a collection of standalone modules which can be run in an IDE
like [PyCharm](https://www.jetbrains.com/pycharm/) and in the browser like
[Repl.it](https://repl.it/languages/python3). Even a plain old terminal will work
with the examples. Most lines have carefully crafted comments which guide a reader
through what the programs are doing step-by-step.

**Serve as a pure guide** for those who want to revisit core Python concepts.
Only builtin libraries are leveraged so that these concepts can be conveyed without
the overhead of domain-specific concepts. As such, popular open-source libraries
and frameworks (i.e. `sqlalchemy`, `requests`, `pandas`) are not installed.
However, reading the source code in these frameworks is inspiring and highly
encouraged if your goal is to become a true
[Pythonista](https://www.urbandictionary.com/define.php?term=pythonista).

## Table of contents :books:

- **Design Philosophy**: [The Zen of Python](https://www.python.org/dev/peps/pep-0020/)
- **Style Guide**: [Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
- **Language Mechanics**
    - **Syntax**
        - Variable: [Built-in literals](ultimatepython/syntax/variable.py)
        - Expression: [Numeric operations](ultimatepython/syntax/expression.py)
        - Conditional: [if | if-else | if-elif-else](ultimatepython/syntax/conditional.py)
        - Loop: [for-loop | while-loop](ultimatepython/syntax/loop.py)
        - Function: [def | lambda](ultimatepython/syntax/function.py)
    - **Data Structures**
        - List: [List operations](ultimatepython/data_structures/list.py)
        - Tuple: [Tuple operations](ultimatepython/data_structures/tuple.py)
        - Set: [Set operations](ultimatepython/data_structures/set.py)
        - Dict: [Dictionary operations](ultimatepython/data_structures/dict.py)
        - Comprehension: [list | tuple | set | dict](ultimatepython/data_structures/comprehension.py)
    - **Classes**
        - Basic class: [Basic definition](ultimatepython/classes/basic_class.py)
        - Abstract class: [Abstract definition](ultimatepython/classes/abstract_class.py)
        - Exception class: [Exception definition](ultimatepython/classes/exception_class.py)
        - Iterator class: [Iterator definition | yield](ultimatepython/classes/iterator_class.py)
    - **Advanced**
        - Decorator: [contextlib | wraps](ultimatepython/advanced/decorator.py)
        - Metaclass: [Metaclass definition](ultimatepython/advanced/meta_class.py)
        - Method Resolution Order: [mro](ultimatepython/advanced/mro.py)

## Additional resources :earth_americas:

As you start applying Python fundamentals to the real world, read over
code examples and project ideas from other well-regarded resources.

Here are some GitHub repositories to get started with:

- [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) (Interview)
- [faif/python-patterns](https://github.com/faif/python-patterns) (Design)
- [vinta/awesome-python](https://github.com/vinta/awesome-python) (Examples)
- [geekcomputers/Python](https://github.com/geekcomputers/Python) (Examples)
- [karan/Projects](https://github.com/karan/Projects) (Ideas)
- [MunGell/awesome-for-beginners](https://github.com/MunGell/awesome-for-beginners) (Ideas)
