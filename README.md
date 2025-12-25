
# Project Setup Guide

Welcome! This guide will help you **install all the dependencies** for this project using the `requirements.txt` file. Follow the steps below carefully to get your environment ready. 🚀

---

## **Step 1: Open Terminal / Command Prompt**

- **Windows:** Press `Win + R`, type `cmd`, and hit Enter.  
- **Mac/Linux:** Open your Terminal app.

---

## **Step 2: Navigate to the Project Folder**

Use the `cd` command to go to the folder where your project and `requirements.txt` file are located.  

```bash
cd path/to/your/project
````

Example:

```bash
cd C:\Users\YourName\Projects\MyProject   # Windows
cd /Users/YourName/Projects/MyProject     # Mac/Linux
```

---

## **Step 3: Check Python and pip Installation**

Make sure Python and pip are installed:

```bash
python --version
pip --version
```

or on Mac/Linux if using Python 3:

```bash
python3 --version
python3 -m pip --version
```

> ⚠️ If pip is not installed, follow [pip installation guide](https://pip.pypa.io/en/stable/installation/).

---

## **Step 4: Install Dependencies**

Run the following command to install all packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

Or, on Mac/Linux with Python 3:

```bash
python3 -m pip install -r requirements.txt
```

This will install all required packages with the correct versions.

---

## **Step 5: Verify Installation**

Check if a package was installed successfully:

```bash
pip show langchain
```

List all installed packages:

```bash
pip list
```

---

## **Tips & Notes**

* If a package is missing, install it manually:

```bash
pip install package_name
```

* It's recommended to use a **virtual environment** to avoid conflicts with other projects:

```bash
python -m venv env
source env/bin/activate    # Mac/Linux
env\Scripts\activate       # Windows
```

* After activating the virtual environment, run the `pip install -r requirements.txt` command again.

---

✅ **You're all set!** Your project environment is now ready to use. Enjoy coding! 🎉

```



