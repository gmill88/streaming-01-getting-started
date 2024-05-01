# streaming-01-getting-started

> Get started with Python for streaming analytics

We assume no prior programming experience and that you want to 
get productive as quickly as possible.

This project uses only content from the Python Standard Library. 
No project virtual environment is required. 

These are popular industry tools - we'll practice with them a lot. 
Getting good at them helps you build better analytics projects more efficiently. 

## Prerequisites

You should have these downloaded and installed on your machine:

1. Python 3.10 or higher
1. VS Code
1. VS Code Extension: Python
1. Git (configured with user.name and user.email - the same email you use for GitHub)

Remember:

- **Spacing, Spelling, Capitalization**: When programming, these are critical. Always double-check!

---

## Open Project Folder in VS Code


## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal) and verify your software is installed and configured.

```shell
git --version
git config user.name
git config user.email
python3 --version
python3 -m pip install --upgrade pip wheel
```

## Execute Utility Script (Diagnostics)

With your repo folder open in VS Code:

1. Click util_about.py.
1. If VS Code prompts, install the recommended Python extension.
1. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.12.x).
1. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
1. From the dropdown, choose your default Python version.

Use the terminal and the python command to execute the Python script. 

1. Use your VS Code terminal window from above or open a new terminal window (View / Terminal) in VS Code.

```shell
python3 util_about.py
```
---


## Explore & Execute Project Scripts

With our project repository folder open in VS Code, and having confirmed that we can execute a Python script successfully, it's time to explore. 

Open, read, and run each project script (each file will have a .py extension) in order.

You don't need to fully understand the code yet. 
Instead, read the code and try to figure out what each file is doing.

When you finish, you'll have an idea of some things possible using just the Python standard library. 
You'll have generated several new data files.
The streaming process will run continuously for quite a while. 
Read the comments in the file to learn how to stop the process.

```shell
python3 process_batch_A.py
```

```shell
python3 process_batch_B.py
```

```shell
python3 process_batch_C.py
```

```shell
python3 process_streaming_0.py
```
---

## Update Edit README

Edit this README.md file. It uses Markdown, a simple and easy markup language.

- Keep the prerequisites and task headings. 
- Within the task headings, record only the commands that worked on YOUR machine. 
- Remove unnecessary instructions once you've mastered them.
- Add any additional notes that will help you in the future.


### Option B: Use Git Bash or Terminal Commands (Easy as well):

Open a new `Git Bash` or Terminal window. Run the following commands one at a time.
They will first add all the files (add "dot"). 
Then they will commit the changes with a message. 
Finally, they will push the changes up to GitHub.

```
git add .
git commit -m "initial results"
git push origin main
```

Open a browser and view your GitHub repository. 
Verify your new files have been successfully pushed to GitHub. 

✔️ Make sure your git add / commit / push completes successfully. 
If not, post screenshots, error messages, and questions in the discussion.
We've all been there when first learning Git and we can help. 
---


