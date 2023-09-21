
#  Secret Auction Program {Python Game}
The provided code is a simple implementation of an auction bidding system. Here's a breakdown of its functionality:

1. **Initialize an empty dictionary**: `auction_dict = {}` This dictionary will store the names of the bidders as keys and their corresponding bids as values.

2. **Collect bidder information**: The `while True:` loop runs indefinitely, collecting the name and bid of each bidder. The name and bid are stored in the `auction_dict`.

3. **Check for more bidders**: After each bid, the code asks if there are any other bidders. If the answer is 'no', the loop breaks and no more bids are collected.

4. **Clear console output**: Depending on the operating system (Windows or others), the console output is cleared using `os.system('cls')` or `os.system('clear')`. This makes sure that the next bidder doesn't see the previous bidder's information.

5. **Determine the highest bid**: After all bids are collected, the code iterates over `auction_dict` to find the highest bid and the corresponding bidder.

6. **Print the result**: Finally, it prints out the name of the highest bidder and their bid.

Please note that this code should be run in a console or command prompt for proper functionality of clearing console output. It might not work as expected in some environments like Jupyter notebooks or online Python editors.
#  Acknowledgements
I would like to thank Dr. Angela Yu.
## Authors

- [@Sookchand](https://github.com/Sookchand)


## Screenshots

![bid](https://github.com/Sookchand/Secret-Auction-Program/assets/34344439/a4212d61-3fb6-45d2-bbe5-1131447740ec)



## Tech Stack
The code is written in Python, a popular high-level programming language. Here are the technologies and concepts used in this code:

1. **Python Built-in Functions**: The code uses built-in Python functions such as `input()` for taking user input, `int()` for converting the input to an integer, and `print()` for displaying output.

2. **Python Standard Libraries**: The `os` and `platform` modules are part of Python's standard library. The `os` module provides a way of using operating system dependent functionality like clearing the console (`os.system('cls')` or `os.system('clear')`). The `platform` module is used to access underlying platform's data, such as, hardware, operating system, and interpreter version information.

3. **Python Data Structures**: The code uses a dictionary (`auction_dict`) to store the names of the bidders as keys and their corresponding bids as values.

4. **Control Flow**: The code uses a `while` loop to continuously ask for new bidders until there are none left. It also uses an `if` statement to check the operating system type and to determine the highest bid.

5. **Importing Modules**: The code imports a custom module named `bid`, which seems to contain a variable `logo`. This suggests that the code is part of a larger program, and `bid.py` is another file in the same project.

6. **String Formatting**: The code uses f-string formatting (e.g., `f"The highest bidder is {highest_bidder} with a bid of ${highest_bid}"`) to create a string that includes the highest bidder's name and bid.


## Documentation
Here are the documentation links for the technologies and concepts used in the code:

1. **Python Built-in Functions**: Python's built-in functions like `input()`, `int()`, and `print()` are part of Python's standard library. You can find more information about these in the [Python Built-in Functions documentation](^1^).

2. **Python Standard Libraries**: The `os` and `platform` modules are part of Python's standard library. The `os` module provides a way of using operating system dependent functionality. The `platform` module is used to access underlying platform's data. You can find more information about these in the [Python os module documentation](^5^) and [Python platform module documentation](^9^).

3. **Python Data Structures**: Python provides several built-in data structures including dictionaries used in this code. You can find more information about these in the [Python Data Structures documentation](^14^).

4. **Control Flow**: Python provides several control flow tools including `while` loops and `if` statements used in this code. You can find more information about these in the [Python Control Flow documentation](^19^).

5. **Importing Modules**: In Python, you can use the import statement to bring in certain parts of another module into your current module. You can find more information about this in the [Python Importing Modules documentation](^24^).

6. **String Formatting**: Python provides several ways to format strings. In this code, f-string formatting is used. You can find more information about this in the [Python String Formatting documentation](^27^). 

Please note that these links point to the official Python documentation which is a comprehensive resource for Python programming.

Source: Conversation with Bing, 9/21/2023
(1) Built-in Functions — Python 3.11.5 documentation. https://docs.python.org/3/library/functions.html.
(2) os — Miscellaneous operating system interfaces — Python 3.11.5 .... https://docs.python.org/3/library/os.html.
(3) platform — Access to underlying platform’s identifying data — Python 3. .... https://docs.python.org/3/library/platform.html.
(4) 5. Data Structures — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/datastructures.html.
(5) 4. More Control Flow Tools — Python 3.7.17 documentation. https://docs.python.org/3.7/tutorial/controlflow.html?highlight=range.
(6) 5. The import system — Python 3.11.5 documentation. https://docs.python.org/3/reference/import.html.
(7) string — Common string operations — Python 3.11.5 documentation. https://docs.python.org/3/library/string.html.
(8) builtins — Built-in objects — Python 3.11.5 documentation. https://docs.python.org/3/library/builtins.html.
(9) python - How to see documentation of inbuilt functions on Jupyter .... https://stackoverflow.com/questions/47642683/how-to-see-documentation-of-inbuilt-functions-on-jupyter-notebook.
(10) builtins – builtin functions and exceptions - MicroPython. https://docs.micropython.org/en/latest/library/builtins.html.
(11) Chapter 16 - The os Module — Python 101 1.0 documentation. https://www.python101.pythonlibrary.org/chapter16_os.html.
(12) os – basic “operating system” services — MicroPython latest documentation. https://docs.micropython.org/en/latest/library/os.html.
(13) python - Documentation URL of os module - Stack Overflow. https://stackoverflow.com/questions/69933384/documentation-url-of-os-module.
(14) Platform Module in Python - GeeksforGeeks. https://www.geeksforgeeks.org/platform-module-in-python/.
(15) How do I document a module in Python? - Stack Overflow. https://stackoverflow.com/questions/44084/how-do-i-document-a-module-in-python.
(16) Our Documentation | Python.org. https://www.python.org/doc/.
(17) pywin32 · PyPI. https://pypi.org/project/pywin32/.
(18) Common Python Data Structures (Guide) – Real Python. https://realpython.com/python-data-structures/.
(19) Python - Data structures Tutorial - Online Tutorials Library. https://www.tutorialspoint.com/python_data_structure/index.htm.
(20) Intro to data structures — pandas 2.1.0 documentation. https://pandas.pydata.org/docs/user_guide/dsintro.html.
(21) Data Structures – Real Python. https://realpython.com/tutorials/data-structures/.
(22) Python Control Flow - Python Cheatsheet. https://www.pythoncheatsheet.org/cheatsheet/control-flow.
(23) Python Break, Continue and Pass: Python Flow Control • datagy. https://datagy.io/python-break-continue-pass/.
(24) GitHub - python-control/python-control: The Python Control Systems .... https://github.com/python-control/python-control.
(25) 4. More Control Flow Tools — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/controlflow.html.
(26) Importing Modules — Python 3.11.5 documentation. https://docs.python.org/3/library/modules.html.
(27) Importing Modules — Python 3.11.5 documentation. https://docs.python.org/3/c-api/import.html.
(28) Built-in Types — Python 3.11.5 documentation. https://docs.python.org/3/library/stdtypes.html.
(29) Python String Formatting - W3docs. https://www.w3docs.com/learn-python/python-string-formatting.html.
(30) Python String Formatting - W3Schools. https://www.w3schools.com/python/python_string_formatting.asp.
(31) Python String Formatting Best Practices – Real Python. https://realpython.com/python-string-formatting/.
(32) undefined. https://docs.python.org/.
(33) undefined. http://www.python.org/dev/peps/pep-0257/.
(34) undefined. http://python-control.readthedocs.org/.
(35) undefined. https://github.com/python-control/python-control/issues.
(36) undefined. http://sourceforge.net/p/python-control/mailman/.

## Lessons Learned
The lesson that can be learnt from this solution is:

1. **Understanding Python Basics**: The program uses basic Python concepts such as variables, loops, conditionals, and functions. This helps reinforce understanding of these fundamental concepts.

2. **Working with Python Data Structures**: The program uses a dictionary to store bidder information. This provides practice in using one of Python's built-in data structures and understanding when and how to use it.

3. **User Input and Output**: The program takes user input and prints output to the console. This helps understand how to interact with users in a console application.

4. **Importing Modules**: The program imports modules from Python's standard library (`os` and `platform`). This provides experience in using external libraries and understanding how they can extend the functionality of Python.

5. **Error Handling**: While not explicitly included in the code, developing this program might lead to encountering and handling errors (e.g., what if a user enters a non-numeric bid?). This can lead to learning about error handling in Python.

6. **Code Organization**: The code is organized into a main loop that collects user input, followed by processing that input (determining the highest bid). This provides a lesson in structuring code in a logical and organized manner.

7. **Platform Dependent Code**: The code uses different commands to clear the console depending on the operating system. This provides an understanding of how to write code that can run on multiple platforms.

8. **String Formatting**: The use of f-string formatting in the print statement is a good introduction to this powerful feature of Python.
# Hi, I'm Sookchand! 👋

Strive to improve with each passing moment, surpassing the person I was in the previous minute, the previous hour, and even the person you were yesterday.
## 🚀 About Me
I have experience as a data scientist and machine learning engineer. I have worked on projects involving the development of predictive models, the optimization of machine learning algorithms, and the deployment of machine learning models. I have also worked on projects involving the analysis of large datasets, the development of data-driven insights, and the creation of data visualizations.
## 🛠 Skills
I possess a wide range of skills including:

- **Data Analysis**: Proficient in Data Exploration and Visualization, Model Evaluation and Analysis, and Regression Analysis.
- **Machine Learning**: Experienced in Neural Network and Deep Learning, Supervised Learning (including Classification, Regression, and Time Series), Decision Trees and Random Forests, Ensemble Learning, and Hyperparameter Tuning.
- **Libraries and Frameworks**: Skilled in using TensorFlow 2.0, NumPy, Scikit Learn, Keras, Pandas, React.js, Node.js, Express.js with Node.js.
- **Big Data Technologies**: Familiar with Hadoop, Apache Spark, Kafka, and Apache Flink.
- **Image Processing**: Capable of performing Image Recognition and Classification, and Transfer Learning.
- **Programming Languages**: Proficient in Python and R. Also have experience with HTML, CSS, JavaScript ES6, DOM, JQuery.
- **Database Management**: Knowledgeable in SQL and MongoDB along with Mongoose.
- **Web Development**: Experienced in HTML, CSS, Bootstrap 4, JavaScript ES6, DOM, JQuery.
- **Version Control Systems**: Comfortable with Git, GitHub.
- **Data Visualization Tools**: Proficient in Tableau and Power BI.
- **Authentication and Security**: Familiar with various authentication and security protocols.
- **Other Skills**: Comfortable working with GPU on Google Collab. Familiar with Unix Command-Line.

This diverse skill set allows me to tackle a variety of data science and web development projects.
