# Claude-api
Building with the Claude API

---

## 1. Prerequisites
- Install [Python 3](https://www.python.org/downloads/macos/) (check with `python3 --version`).
- Install the **Python extension** in VS Code (by Microsoft).

---

## 2. Project Setup

### Step 1: Clone or Create Project Folder
mkdir Claude-api
cd Claude-api

### Step 2: Create Virtual Environment

python3 -m venv venv
source venv/bin/activate

### Step 3: Create Main File and requirment file

touch main.py
echo "requests" > requirements.txt
pip install -r requirements.txt

### Step 4: Run project

python main.py