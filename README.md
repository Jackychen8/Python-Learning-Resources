# Python
Python is an easy to learn language many beginners to coding choose as their first programming language and it is not limited to web development, as you can build games and applications for academical research with it. If you are new to programming or simply interested in learning Python, here are some resources you can use.

## Good Concepts to Know for Best Practices Python Development
1. Isolating your developer space to avoid running into altering the global python environment.
  - Problem:
> If you don't specify a unique python environment, by default, you will use the global python environment of your computer.
> Other apps or your computer may rely on specific versions of python modules so if you start installing new modules, you could break things.
> Also, you will probably work on multiple python projects and you don't want their dependencies to interfere with each other.
> In a professional environment, you will need to collaborate with other developers. In these cases, you want to be able to share the exact
> dependencies of your project so the project can be recreated and run from any computer. Working in a unique python environment (venv) will
> make it trivial to check what modules your project has used. This manifests in the requirements.txt file which is then used by others
> to install modules.
  - Solution:
    - virtualenv
    - conda
2. Code Style Standards
  - Problem:
> Python allows your code to be written in vastly different ways but you generally want it to be easy to read and understand.
> In a professional environment, you want your code to be just as easy to understand for someone else as yourself so many will
> adhere to coding styles or guidelines. In Python, the accepted standard is PEP8.
  - Solution:
    - [PEP8](https://www.python.org/dev/peps/pep-0008/)
    - Style Enforcement Tools [pylint](https://www.pylint.org/), [pyflakes](https://github.com/PyCQA/pyflakes)
3. Unit Testing (pytest, unittest, doctest)
4. Commenting
  - Problem:
> When looking at new code or reviewing code, you are generally working on one piece of a larger code base.
> It may be difficult or impossible to know what you can expect to receive in your code or, for others, to know
> what they may expect from your code.
> Structuring your comments in a standardized way will allow tools like Sphinx to generate documentation for you.
  - Solution:
    - Tools: Sphinx (Auto-generate documentation)
    - Comment Styles [google](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html)
5. Debug & Learning Techniques
  - Problem:
> If you don't understand how something works or what is available from some python module/class/function, you can use the help() function.
  - Solution:
    - help(x): Provide the comments written for the module/class/function specified as x as written documentation (similar to 'man')
    - var(x): all methods and variables tied to x (One of these involves inheritance chain)
    - dir(x): all methods and variables tied to x
    - id(): address in memory

## Best Collection of Python Tutorials
  - Learning Guide- [Learn Python Online](https://www.codementor.io/learn-python-online)
  - Tutorial- [Python Tutorials for Beginners and Programmers](https://www.codementor.io/python/tutorial)

## Online Help
  - Online Experts- [1:1 Python Help from Proven Experts](https://www.codementor.io/python-experts)

## Platform for Python Tutorials
  - [Bucky's Room](https://buckysroom.org/videos.php?cat=98)
  - [Think Python](http://www.greenteapress.com/thinkpython/)
  - [Learn Python](http://www.learnpython.org/)
  - [Python for You and Me](http://pymbook.readthedocs.org/en/py3/)
  - [Learn Python the Hard Way](http://learnpythonthehardway.org/book/)
  - [edX Introduction to Computer Science and Programming Using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-5)

## General Topics for Beginners
  - [Python Tutorials for Beginners and Programmers ](https://www.codementor.io/python/tutorial)
  - [Python Beginner Tutorial: for Loops and Iterators](https://www.codementor.io/python/tutorial/python-generators-and-iterators)
  - [Python 2.7 vs Python 3.4 ─ What should Python Beginners choose?](https://www.codementor.io/python/tutorial/python-2-7-vs-python-3-4)
  - [Wishful Coding in Python: A Problem Solving Philosophy](https://www.codementor.io/python/tutorial/wishful-coding-python-solving-big-problems)
  - [Introduction to Python Decorators](https://www.codementor.io/python/tutorial/introduction-to-decorators)
  - [Beginner's Guide to Debugging Python: Print Statements](https://www.codementor.io/python/tutorial/how-to-debug-python-code-beginners-print-line)
  - [How to Create Custom Exceptions in Python](https://www.codementor.io/python/tutorial/python-custom-exception)
  - [A SQLAlchemy Cheat Sheet](https://www.codementor.io/python/tutorial/understanding-sqlalchemy-cheat-sheet)
  - [Python Framework Comparison: Django vs. Pyramid](https://www.codementor.io/python/tutorial/django-vs-pyramid-python-framework-comparison)
  - [How to Set up NumPy on a 64 bit Windows OS](https://www.codementor.io/numpy/tutorial/installing-numpy-64-bit-windows)
  - [Python Q&A with #1 Stack Overflow Python Expert](https://www.codementor.io/python/tutorial/stack-overflow-python-expert-answers-questions)
  - [Stack Overflow Legend Martijn Pieters: Python Optimization and How it Can Affect Your Code](https://www.codementor.io/python/tutorial/stack-overflow-martijn-pieters-python-optimization)
  - [6 Useful Python Libraries Recommended by #1 Stack Overflow Answerer](https://www.codementor.io/python/tutorial/6-useful-python-libraries)
  - [Martijn Pieters on the Future of Django](https://www.codementor.io/python/tutorial/martijn-pieters-future-django)
  - [Python Internals: Codementor Office Hours with Martijn Pieters](https://www.codementor.io/python/tutorial/python-internals-codementor-office-hours-martijn-pieters)
  - [Building a Simple Snake Game with Python](https://www.codementor.io/python/tutorial/build-snake-game-using-curses)

## Data Science with Python
  - [Data Frames with Python & R](https://www.codementor.io/python/tutorial/python-vs-r-for-data-science-data-frames-i), [Part 2](https://www.codementor.io/python/tutorial/python-vs-r-data-science-data-frames-ii)
  - [Exploratory Data Analysis](https://www.codementor.io/python/tutorial/data-science-python-r-exploratory-data-analysis-visualization)
  - [Dimension Reduction & Clustering](https://www.codementor.io/python/tutorial/data-science-python-pandas-r-dimensionality-reduction)
  - [Sentiment Classification Using Linear Methods](https://www.codementor.io/python/tutorial/data-science-python-r-sentiment-classification-machine-learning)
  - [Building a Wine Review & Recommendation Site with Django](https://www.codementor.io/python/tutorial/get-started-with-django-building-recommendation-review-app), [Part 2](https://www.codementor.io/python/tutorial/build-data-product-django-user-management), [Part 3](https://www.codementor.io/python/tutorial/build-data-products-django-machine-learning-clustering-user-preferences)

## Python & Apache Spark
  - [Getting Data into the basic Spark data structure: Resilient Distributed Datasets](https://www.codementor.io/spark/tutorial/spark-python-rdd-basics), [Part 2](https://www.codementor.io/spark/tutorial/spark-python-data-aggregations)
  - [Machine Learning Library (MLlib) Basic Statistics & Exploratory Data Analysis](https://www.codementor.io/spark/tutorial/mllib-basic-statistics-exploratory-data-analysis)
  - [MLlib Logistic Regression](https://www.codementor.io/spark/tutorial/spark-mllib-logistic-regression)
  - [MLlib Decision Trees](https://www.codementor.io/spark/tutorial/spark-python-mllib-decision-trees)
  - [SQL & DataFrames](https://www.codementor.io/spark/tutorial/python-spark-sql-dataframes)
  - [Building a Movie Recommendation Service with Apache Spark & Flask](https://www.codementor.io/spark/tutorial/building-a-recommender-with-apache-spark-python-example-app-part1), [Part 2](https://www.codementor.io/spark/tutorial/building-a-web-service-with-apache-spark-flask-example-app-part2)

## Tips
  - [Creating An Asset Pipeline in Python](https://www.codementor.io/python/tutorial/creating-an-asset-pipeline-in-python-with-paver)
  - [Caching Angular Partials with Python](https://www.codementor.io/python/tutorial/html-optimization-caching-angularjs-partials-templates)
  - [How do I remove the first and last rows and columns from a 2D numpy array?](https://www.codementor.io/tips/2843378231/how-do-i-remove-the-first-and-last-rows-and-columns-from-a-2d-numpy-array)
  - [How to check keys in two levels loop? ](https://www.codementor.io/tips/6813274333/how-to-check-keys-in-two-levels-loop)
  - [Python array unpacking error: need more than 3 values ](https://www.codementor.io/tips/3317328246/python-array-unpacking-error-need-more-than-3-values)
  - [scheduling events with a while loop and time.sleep](https://www.codementor.io/tips/1344523786/scheduling-events-with-a-while-loop-and-time-sleep)
  - [Fetching an RSS feed and converting it into a json response](https://www.codementor.io/tips/3493772831/fetching-an-rss-feed-and-converting-it-into-a-json-response)
  - [Opencv: display contours](https://www.codementor.io/tips/4930721378/opencv-display-contours)
  - [Django form choices loaded from database are not updatedCan't figure out what's wrong with my method](https://www.codementor.io/tips/4933721348/can-t-figure-out-what-s-wrong-with-my-method)
  - [Different initial values in a Django formset](https://www.codementor.io/tips/0731824832/different-initial-values-in-a-django-formset)
  - [Why does python's struct think little-endian and big-endian imply different lengths?](https://www.codementor.io/tips/0818274433/why-does-python-s-struct-think-little-endian-and-big-endian-imply-different-lengths)
  - [Comparing two class types in python](https://www.codementor.io/tips/6130438872/comparing-two-class-types-in-python)
  - [How can I get Travis-CI to recognize and open external files during testing](https://www.codementor.io/tips/8102473038/how-can-i-get-travis-ci-to-recognize-and-open-external-files-during-testing)


## Videos
  - [Carte-Blanche, a Django Permission Framework for Rapid Prototyping, with its creator, Eric Neuman ](https://www.codementor.io/officehours/6962831504/carte-blanche-a-django-permission-framework-for-rapid-prototyping-with-its-creator-eric-neuman)
  - [Introduction to Machine Learning & NLP: Building a Spam Classifier](https://www.codementor.io/officehours/1385095426/building-a-spam-classifier)
  - [Stack Overflow Legend Martijn Pieters: Python Optimization and How it Can Affect Your Code](https://www.codementor.io/officehours/9015644327/stack-overflow-legend-martijn-pieters-python-optimization-and-how-it-can-affect-your-code)


## Documentations
  - [Python Documentations](https://www.python.org/doc/)

## Courses
  - [Data Camp (Data Science)](https://www.datacamp.com/)
  - [Live Python Class](https://www.codementor.io/classes/learn-python-live)
  - [MIT Introduction to Computer Science and Programming](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00sc-introduction-to-computer-science-and-programming-spring-2011/)
  - [Programming for Everybody (Python)](https://www.coursera.org/course/pythonlearn)
  - [Google's Python Class](https://developers.google.com/edu/python/?hl=de-DE&csw=1)
  - [Lynda.com](http://www.lynda.com/Python-training-tutorials/415-0.html)
  - [Intro to Computer Science](https://www.udacity.com/course/ud036)
  - [Code School's Try Python](https://www.codeschool.com/courses/try-python)


## Developer Tools
  - [IPython](https://ipython.org/)
  - [PythonAnywhere](https://www.pythonanywhere.com/)
  - [PyDev](http://pydev.org/)
  - [PyCharm](http://www.jetbrains.com/pycharm/)
  - [Flake8Lint](https://github.com/dreadatour/Flake8Lint)
  - [WingWare Python IDE](https://wingware.com/)
  - [Pytest](http://pytest.org/latest/)
  - [Mock](http://www.voidspace.org.uk/python/mock/)
  - [PyLint](http://www.pylint.org/)
  - [Scrapy](http://scrapy.org/)
  - [Robobrowser](http://robobrowser.readthedocs.org/en/latest/)
  - [PyGame](http://pygame.org/news.html)

