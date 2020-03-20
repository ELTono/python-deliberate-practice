# python-deliberate-practice
## Motivation
As a part of my journey in becoming a better full stack data scientist , I decided to improve my python skills to be able to do production level coding by writing modular and reusable code. I have seen that an important part of machine learning is actually deploying the model and have a good practices in software engineering. For this reason, mastering python as language for ML would be very useful in my path to improve my skills. I must mention this learning plan is based in the following post and git repository: https://medium.com/@rchang/how-i-build-learning-projects-part-i-54dbaad68961 - https://github.com/robert8138/python-deliberate-practice/blob/master/README.md. This repository is pretty much based on that with just a few changes to adjust it to my own goals. On top of this python-deliberate-practice, I will also be creating other practice sections for topis like General ML, Experimentation and Devops.
## Deliberate Practice
I consider that the best way to hone my skills is by doing little projects that help me to put in practice whatever theory I read about python. I can combine a mix of self-activities with activities in my current job. 

* __Identify the Top Performers__: Given that in my current job I am the first data scientist, I cannot have a proper role model for ML but maybe the data engineer can help me check my general python program. Also meetups should be a good starting to meet more senior people in data science.

* __Targeted practice__: If I force myself to do most of the plots in dashboards using matplot lib instead of the built-in graphs I would be able to get the practice and get better at making good plots.

* __Immediate Feedbacks__: I think for this part it is going to be hard given I cannot tell people to check my pandas code. The best I can do is to start working with the DE to implement some of my python ideas into tables in our database.

## Performance goals
* __[Immediate]__ Learn about the best ways to write pythonic code.
* __[Short term]__ First, to refresh and learn all the basic data structures for data science. Second, write modular and tested code (also including parsing data from json files). Finally, improve my production level code by mastering the uses of classes and practice by writing my own sklearn estimators to build pipelines.

## Project Goals
* __Outcome__ : I want to improve my production level code skills. This means all my code would be as pythonic as possible (like following PEP 8, using try and assert, correct docstrings and standards) and with a good use of OOP to create classes to handle any data pipeline from cleaning to modeling.

* __Curriculum__: Everything from data structures to all basic materials in Pandas/Matplotlib combo. Learn about OOP, unit test and working with the cloud and github.

* __Timeframe__: All basic structures, basic task and classes by the end of 2019. Then from there I may start including more advanced concepts like optimizing my code for speed and other libraries like dask.

## Project Milestones
* **Learning Python & Best Practices**
    * [Build On Top of the Basics: Python Progression]
    * [Drastically Improve Your Understanding: Jeff Knupp: Python's Execution Mode]
    * [Nate Batchelder: Loop like a native]
    * [Columbia Data Scientist Style Guide]

* **Writing Pythonic Code**
    * Guidelines For Writing Pythonic Code
        * Function: Use *args and **kwargs to accept arbitrary arguments in function definition
        * Tuples: effective unpacking, use _ for placeholder, swap values without tmp variables
        * List/Dict/Set: list comprehension, dict comprehension. dict.get, set comprehension
        * Strings: use .format, use .join
        * Classes: use __ __ in function and variable name to mark private variables
        * Generator: use generator to lazily load a infinite sequence
        * Modules: writing modules for encapsulation
        * Formatting: pep8 standards
        * Executable script: __name__ = __main__
        * Import: The right way to do imports
    * [Writing Idiomatic Python - Jeff Knupp]
    * [Stanford CS 41: Idiomatic Python]
    * [Another Tutorial On How To Write Pythonic Code]
    * [The art of avoiding nested code]

* **iPython Notebook**
    
    * [Jupyter Notebook tips, tricks and shortcuts]
    * [iPython Notebook Keybinding]

* **Pandas For Data Analysis**

    * Introduction to Numpy
        * [Stanford ICME 193: Scientific Python]
    
    * Introduction to Pandas
        * [Dplyr/pandas Vignette Comparison]
        * [Data School Pandas Tutorials]
            * [Data School Pandas Github iPython notebook]
            * [More Pandas Questions Answered]
            * [Other Resources]
        * [Brandon Rhode's Pandas From The Groud Up]
        * [Tom Augspurgur: Pandas]
        * [Chris Albon's notes]

* **Data Visualization**

    * [BIDS: Python Bootcamp: Intro to Matplotlib]: The 800 pound gorilla, everything is customizable, but very low level
    * [Seaborn]: Good for statistical visualization. I still find it a bit limited on the type of simple plots it can do
    * [Bokeh]: Interactive, web browser base data visualization
    * [A Dramatic Tour through Python’s Data Visualization Landscape (including ggplot and Altair)]

* **Writing Object Oriented Programming Python Code**
    
    * [Computational Biology: OOP For Scientist]
    * [Improve Your Python: Jeff Knupp: OOP]
    * [BIDS: Python Bootcamp: OOP]
    * [OPP through machine learning]

* **Writing Functional Programming Python Code**
    
    * [Simeon Franklin's higher order function]
    * [BIDS: Python Bootcamp: Higher order functions]
    * [Improve Your Python: Jeff Knupp: Yield & Generator Explained]
    * [Improve Your Python: Jeff Knupp: Decorator Explained]
    * [Improve Your Python: Jeff Knupp: Context Manager]
    
* **Estimators In Sklearn** 
    * [Scikit-learn Machine Learning Library]
    * [Scikit-learn metrics]
    * [Scikit-learn Pipeline]

* **Testing In Python**
    
    * [Computational Biology: Four Tools For Testing Your Python Code]
    * [Computational Biology: Testing For Scientist]
    * [Improve Your Python: Jeff Knupp: Understanding Unit Testing]
    * [BIDS: Python Bootcamp: Test Driven Development]
    * [Software Carpentry: Testing]
    * [How to Write Testable Code and Why it Matters]
    
* **Good standard practice**
    * [Begginers guide to kickass README]
    * [Enforcing Single Responsibility Principle]
    
## Reference

* [Python Tutor Visualizer]
* [Python For Data Analysis]
* [Stanford CS 41: Python]
* [Berkeley CS 88: Python Data Structure]
* [Harvard CS 109: Data Science]
* [Berkeley BIDS Python bootcamp]
* [Josh Bloom's Python Computing For Data Science]
* [Writing Idiomatic Python - Jeff Knupp]
* [Another Tutorial On How To Write Pythonic Code]
* [Pandas Cookbook]
* [Udemy course]
    

[Teach Yourself Programming in 10 years]:http://norvig.com/21-days.html
[Plateau of Productivity]:http://pbpython.com/plateau-of-productivity.html

[reddit answer]:https://www.reddit.com/r/Python/comments/2tkkxd/considering_putting_my_efforts_into_python/
[Language war]:http://www.dataschool.io/python-or-r-for-data-science/
[advanced R materials]:http://adv-r.had.co.nz/
[basic web applications in Flask]:https://github.com/robert8138/flask-google-calendar-api-project
[data stacks]:https://lab.getbase.com/productive-data-science-python/

[Build On Top of the Basics: Python Progression]:http://stackoverflow.com/questions/2573135/python-progression-path-from-apprentice-to-guru
[Drastically Improve Your Understanding: Jeff Knupp: Python's Execution Mode]:https://www.jeffknupp.com/blog/2013/02/14/drastically-improve-your-python-understanding-pythons-execution-model/
[Nate Batchelder: Loop like a native]:https://www.youtube.com/watch?time_continue=14&v=EnSu9hHGq5o
[Columbia Data Scientist Style Guide]:http://columbia-applied-data-science.github.io/pages/lowclass-python-style-guide.html

[Writing Idiomatic Python - Jeff Knupp]:https://jeffknupp.com/writing-idiomatic-python-ebook/
[Stanford CS 41: Idiomatic Python]:https://drive.google.com/file/d/0B-eHIhYpHrGDNGZCYUN6SVB1OGc/view
[Another Tutorial On How To Write Pythonic Code]:http://safehammad.com/downloads/python-idioms-2014-01-16.pdf

[BIDS: Python Bootcamp: IPython Notebook]:https://www.youtube.com/watch?v=HrylK8I1ALs&index=3&list=PLKW2Azk23ZtSeBcvJi0JnL7PapedOvwz9
[Jupyter Notebook tips, tricks and shortcuts]:https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/
[iPython Notebook Keybinding]:https://www.webucator.com/blog/wp-content/uploads/2015/07/IPython-Notebook-Shortcuts.pdf

[BIDS: Python Bootcamp: Intro to Numpy]:https://www.youtube.com/watch?v=PDOsOcG0m-Q
[Stanford CME 193: Scientific Python]:http://web.stanford.edu/class/cme193/syllabus.html
[Dplyr/pandas Vignette Comparison]:http://nbviewer.jupyter.org/gist/TomAugspurger/6e052140eaa5fdb6e8c0
[Data School Pandas Tutorials]:http://www.dataschool.io/easier-data-analysis-with-pandas/
[Data School Pandas Github iPython notebook]:https://github.com/justmarkham/pandas-videos
[More Pandas Questions Answered]:https://www.youtube.com/watch?v=CWRKgBtZN18&list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y&index=31
[Other Resources]:http://www.dataschool.io/best-python-pandas-resources/
[Brandon Rhode's Pandas From The Groud Up]:https://www.youtube.com/watch?v=5JnMutdy6Fw
[Tom Augspurgur: Pandas]:https://www.youtube.com/watch?v=otCriSKVV_8
[BIDS: Python Bootcamp: Scipy Pandas]:https://www.youtube.com/watch?v=bgIZAeNpL1U
[Coursera: Introduction to Data Science in Python]:https://www.coursera.org/learn/python-data-analysis/home/welcome
[Chris Albon's notes]:http://chrisalbon.com/

[BIDS: Python Bootcamp: Intro to Matplotlib]:https://www.youtube.com/watch?v=j5P822TSCKs
[Seaborn]:https://stanford.edu/~mwaskom/software/seaborn/
[Bokeh]:http://bokeh.pydata.org/en/latest/
[A Dramatic Tour through Python’s Data Visualization Landscape (including ggplot and Altair)]:https://dansaber.wordpress.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/

[Computational Biology: OOP For Scientist]:http://tjelvarolsson.com/blog/object-oriented-programming-for-scientists/
[Improve Your Python: Jeff Knupp: OOP]:https://jeffknupp.com/blog/2014/06/18/improve-your-python-python-classes-and-object-oriented-programming/
[BIDS: Python Bootcamp: OOP]:https://www.youtube.com/watch?v=HQ0q6oMpOEs
[OPP through machine learning]:https://dziganto.github.io/classes/data%20science/linear%20regression/machine%20learning/object-oriented%20programming/python/Understanding-Object-Oriented-Programming-Through-Machine-Learning/
[The art of avoiding nested code]: https://www.thepythoncorner.com/2017/12/the-art-of-avoiding-nested-code/

[Simeon Franklin's higher order function]:http://simeonfranklin.com/blog/2013/jun/17/higher-order-functions-python/
[BIDS: Python Bootcamp: Higher order functions]:https://www.youtube.com/watch?v=ob797BA49ZQ
[Improve Your Python: Jeff Knupp: Yield & Generator Explained]:https://jeffknupp.com/blog/2013/04/07/improve-your-python-yield-and-generators-explained/
[Improve Your Python: Jeff Knupp: Decorator Explained]:https://jeffknupp.com/blog/2013/11/29/improve-your-python-decorators-explained/
[Improve Your Python: Jeff Knupp: Context Manager]:https://jeffknupp.com/blog/2016/03/07/improve-your-python-the-with-statement-and-context-managers/

[Scikit-learn Machine Learning Library]:http://www.dataschool.io/machine-learning-with-scikit-learn/
[Scikit-learn metrics]:http://scikit-learn.org/stable/modules/classes.html#module-sklearn.metrics
[Scikit-learn Pipeline]:http://scikit-learn.org/stable/modules/classes.html#module-sklearn.pipeline

[Computational Biology: Four Tools For Testing Your Python Code]:http://tjelvarolsson.com/blog/four-tools-for-testing-your-python-code/
[Computational Biology: Testing For Scientist]:http://tjelvarolsson.com/blog/test-driven-develpment-for-scientists/
[Improve Your Python: Jeff Knupp: Understanding Unit Testing]:https://jeffknupp.com/blog/2013/12/09/improve-your-python-understanding-unit-testing/
[BIDS: Python Bootcamp: Test Driven Development]:https://www.youtube.com/watch?v=hrj8Wo34nvw
[Software Carpentry: Testing]:http://katyhuff.github.io/python-testing/
[How to Write Testable Code and Why it Matters]:https://www.toptal.com/qa/how-to-write-testable-code-and-why-it-matters

[Sharing Your Side Projects]:https://www.youtube.com/watch?v=uRul8QdYvqQ

[Basic Python Logging - Code Session]:https://www.youtube.com/watch?v=PX_xd2YjrsU
[Logging HOWTO]:https://docs.python.org/2/howto/logging.html
[Become A Logging Expert In 30 Minutes]:https://www.youtube.com/watch?v=24_4WWkSmNo

[Click Documentation]:http://click.pocoo.org/5/quickstart/
[Writing A Command-Line Tool In Python]:http://nvie.com/posts/writing-a-cli-in-python-in-under-60-seconds/

[Computational Biology: Using Cookiecutter To Set Up A Project]:http://tjelvarolsson.com/blog/using-cookiecutter-a-passive-code-generator/
[Computational Biology: Creating A Clean Pytyon Development Environment]:http://tjelvarolsson.com/blog/begginers-guide-creating-clean-python-development-environments/
[Computational Biology: How To Generate Beautiful Technical Documentation]:http://tjelvarolsson.com/blog/how-to-generate-beautiful-technical-documentation/
[Computational Biology: Five Steps To Add The Bling Factor Your Python Package]:http://tjelvarolsson.com/blog/five-steps-to-add-the-bling-factor-to-your-python-package/

[Begginers guide to kickass README]:https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3
[Enforcing Single Responsibility Principle]:https://sobolevn.me/2019/03/enforcing-srp
[The Definitive Guide to Python import Statements]: https://chrisyeh96.github.io/2017/08/08/definitive-guide-python-imports.html

[Python Tutor Visualizer]:http://www.pythontutor.com/visualize.html#mode=edit
[Python For Data Analysis]:http://www3.canisius.edu/~yany/python/Python4DataAnalysis.pdf
[Stanford CS 41: Python]:http://stanfordpython.com/
[Berkeley CS 88: Python Data Structure]:http://cs88-website.github.io/
[Harvard CS 109: Data Science]:http://cs109.github.io/2015/
[Berkeley BIDS Python bootcamp]:https://bids.berkeley.edu/news/python-boot-camp-fall-2016-training-videos-available-online
[Josh Bloom's Python Computing For Data Science]:https://github.com/profjsb/python-seminar
[Pandas Cookbook]:http://pandas.pydata.org/pandas-docs/stable/cookbook.html
[Udemy course]:https://www.udemy.com/learning-python-for-data-analysis-and-visualization/?ccManual=&couponCode=DEAL19





