---
marp: true
markdown: 
  html: true
paginate: true
headingDivider: 2
footer: Programming in Python, IITM Online BS Degree in Data Science
---
<style>
  .warning{
    background:rgba(255,255,0,.5)

  }
  .danger{
    color:red

  }
</style>
# Python Orientation
![h:150](/assets/Python.png)
**How to Learn Python :snake:**
Some of the infinite :infinity: number of ways 
# About the course grading
- Want to PASS?
  - Avg(<span class="danger">best 4 of first 6 WTA</span>) >= 40 - OPPE2 and End Term Eligibility
  
  - Avg(<span class="warning">best 5 of first 9 GA+GPA</span>) >= 40 - End Term Eligibility
  - Present in End Term
  - atleast one of the OPPE >=40 
  - T >= 40, where  T = 0.1GAA + 0.1Qz1+ <span class="danger warning">0.4F </span>+ 0.25 max(PE1, PE2) + <span class="danger">0.15 min(PE1, PE2) + 0.05WTA</span> — capped to 100



# Learning Typing
- Learn fast typing if you are not familiar: http://www.typing-lessons.org/.
![w:auto h:250](/assets/image.png) ![h:200](/assets/fingers.gif)
- This helps with programming exams, and most of the other programming courses that you encounter.
- **30 mins per day for 1 month and your will be a master :martial_arts_uniform:**
 
# Learning References for python (Pre-reading)

- **Our own python text book :book:(Try the search  bar in top right)**:  https://bsc-iitm.github.io/python-textbook/
<!-- <iframe src=https://bsc-iitm.github.io/python-textbook/ height=400 width= 300> -->
- **Python's official Documentation**: https://docs.python.org/3/tutorial/index.html
- **[The Hitchhiker's Guide to Python](https://docs.python-guide.org/intro/learning/)** - contains links to multiple python resources.
![h:200](/assets/image-1.png) ![h:200](/assets/python-guide-logo.png)
- **[Tutorials Point](https://www.tutorialspoint.com/python/index.htm)**, **[W3Schools](https://www.w3schools.com/python/python_intro.asp)** 
- **and a bunch of other sites.**


# Different ways to run python code
* As a python file and running it. `python filename.py` or `py filename.py`
* Python REPL `>>>` - running line by line.
* Notebook environments (Colab, Jypter Notebook, Jupyter Lab) - running cell by cell interactively
![h:200](/assets/img-001.png)

# IDEs for Learning and Experimenting

* **[Replit](https://replit.com/)** - online, no setup, used in lectures.
* **[Google Colab](https://colab.research.google.com/)** - Online, no setup, easy to use, interactive, suitable for experimenting.
* **Local python setup with text editor like VS Code, Atom or Sublime** - offline, minimal setup.
* **VS code extension for Jupyter Notebook** - offline, moderate setup, interactive.

# Sites for Practicing Problem solving

* **Course portal** - for course assignments, to get familiar with the interface for OPPE, Not for learning, for practicing.
* **[HackerRank](https://www.hackerrank.com/domains/python?badge_type=python)** - problems for beginners, advanced, section with python specific problems.
* **Leetcode** 
* **HackerEarth** 
* **And a bunch of other sites**
* **AI chatbots(ChatGPT/Bard)** - ask for simple problem statements with sample inputs and output. (Verify inputs and outputs may be incorrect.)

# Python Tutor for Visual Debugging
<script src="https://gist.github.com/livinNectorPOD/93267f259417d71b2307d1a66023d675.js"></script>

# Note on learning from multiple resources
- **Search** for the concept you want to learn in web search through multiple websites for examples try running the sample code in colab or your favorite editor.
- **Play with the code** to understand how it works. 
- **Visualize** to see what happens at each step.
  - **pythontutor** - original website or our own colab to visualize what is happening in each step.
  - **Traditional print** - printing the values, type, len, etc.,
  - **AI and Mermaid(Experimental)** - Ask AI to create a mermaid diagram of a flowchart for a code snippet. Paste it in https://mermaid.live.

# Note for people with prior experience in C/C++
- `for` in C and Python behaves differently.
- Most tasks in python doesn't require an index based loop.
- In python there are more inbuilt functions for doing simple tasks.

# Note on learning using AI Chatbots(ChatGPT/Bard)
* Facts about AI chatbots
  * They can make mistakes.
  * They do not perform actual computation to give you the answer.
  * They are Large Language models.
  * They are still not capable of doing very complex tasks.
  * They are cappable of doing simple programming tasks
  * They can generate sample inputs for you to play with.

# Note on learning using AI Chatbots(ChatGPT/Bard)
* How to use them
  * Ask for examples in a concept, or explain simple algorithms
  * Ask to create sample inputs or driver code to workout.
  * Ask to review your working code, and ask for simpler/pythonic solutions.
  * Ask to make your code more readable using proper naming conventions.
  * Ask to write documentation and comments for your code.

* Dont's
  * Asking AI for just solutions and Using AI code without verifying.
  * **Beware! If AI:robot: can do something, it might replace you.**

# Note on learning by doing projects

* Create a project plan - a simple game, a simple app.
* Not everything requires a GUI, there are TUI, CLI, Notebook Widgets, Forms, etc.
* Use a well-named notebook, a git repo or a replit repl to store your projects online so that you can share it, and you won't lose the code.

# Summary
* **Get to know concepts** - lectures/web/books/AI
* **Play with them** - simple codes, playing around, debugging, pythontutor
* **Practice** - solve problems
* **Get Creative** - Create your problems and find solutions(not just input and print)



# General Keyboard Shortcuts

- **Ctrl (Cmd) + A:** Select all text in a document.
- **Ctrl (Cmd) + X:** Cut selected text.
- **Ctrl (Cmd) + C:** Copy selected text.
- **Ctrl (Cmd) + V:** Paste copied or cut text.
- **Ctrl (Cmd) + Z:** Undo the last action.
  
## **Moving the Cursor**
   - **Left/Right Arrow keys:** Move the cursor one character left or right.
   - **Up/Down Arrow keys:** Move the cursor one line up or down.
   - **Ctrl (Cmd) + Left/Right Arrow keys:** Move the cursor one word left or right.
   - **Home/End:** Jump to the beginning or end of a line.
   - **Ctrl (Cmd) + Home/End:** Jump to the beginning or end of a document.

## **Selecting Text:**
   - **Shift + Arrow keys:** Select text in the direction of the arrow key.
   - **Shift + Ctrl (Cmd) + Left/Right Arrow keys:** Select whole words at a time.
   - **Shift + Home/End:** Select from the cursor position to the beginning or end of the line.
   - **Shift + Ctrl (Cmd) + Home/End:** Select from the cursor position to the beginning or end of the document.

## **Multicursor editing:**
  - This is different for different editors, such as vscode, sublime, atom.
  - In colab, if you place the cursor in a word and press **Ctrl+D** multiple cursors will appear in your editor, and you can change all at once.
  
**Note:** These shortcuts might vary slightly depending on the application you're using. Always refer to the specific software's documentation for the most accurate on keyboard shortcuts.