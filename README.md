# **Pro Analytics 01: Supplier Performance Tracker & Workflow Guide**  
This repository provides a **supplier performance analytics module** alongside a **clear workflow** for setting up Python projects, managing Git repositories, and following a repeatable development process.  

The instructions are divided into three main sections:  

## **First: Set Up Machine & Sign up for GitHub**  
Go to [01-machine-setup](01-machine-setup/MACHINE-SETUP.md) to prepare for Python projects. Start here to set up a machine for the first time (or to upgrade or verify professional tools).  

This section contains **one-time tasks**, including:  
1. View file extensions and hidden files/folders.  
2. Install (or verify) a package manager for your operating system.  
3. Install Python, Git, and Visual Studio (VS) Code.  
4. Configure Git.  
5. Install common VS Code extensions.  
6. Create a folder on your machine to hold your GitHub projects.  
7. Create a GitHub account (join 100 Million Developers!).  

---

## **Second: Initialize a Project**  
Go to [02-Project-Initialization](./02-project-initialization/PROJECT-INITIALIZATION.md) when **starting a new project**.  

This section walks you through the steps to either:  
1. Copy an existing project OR start a new project from scratch.  
2. Clone your new GitHub repo to your machine.  
3. Add common files such as `.gitignore` and `requirements.txt`.  
4. Git add-commit-push the changes to GitHub.  
5. Create a local project virtual environment for Python.  

---

## **Third: Work on the Supplier Performance Analytics Project**  
Go to [03-Repeatable-Workflow](./03-repeatable-workflow/REPEATABLE-WORKFLOW.md) for ongoing development.  

This section provides the **repeatable steps** for working on Python projects while analyzing **supplier performance metrics**, including **delivery reliability, defect rates, and efficiency**.

### **Project Overview**  
This module analyzes **supplier performance**, using Python's `statistics` module to compute **delivery times, reliability scores, and defect rates**.  

### **Features**  
- **Tracks Supplier Performance:** Analyzes **delivery times, reliability scores, and defect rates**.  
- **Computes Key Statistics:** Calculates **min, max, mean, and standard deviation** of supplier delivery times.  
- **Checks Supplier Count Even/Odd:** Implements Python’s modulus operator to verify supplier numbers.  
- **Reusable Analytics Module:** Designed for **integration into broader supply chain systems**.  

### **Installation & Setup**  
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/your-username/supplier-performance-analytics.git
   cd supplier-performance-analytics
   ```
2. **Ensure Python is installed** (>= 3.8)  
   ```sh
   python --version
   ```
3. **Create a Virtual Environment** (recommended)  
   ```sh
   python -m venv .venv
   source .venv/bin/activate  # macOS/Linux
   .\.venv\Scripts\activate   # Windows
   ```
4. **Install Dependencies**  
   ```sh
   pip install -r requirements.txt
   ```
5. **Run the Script**  
   ```sh
   python utils_kiruthikaa.py
   ```

---

## **Repeatable Workflow Steps**  
These steps are typically followed whenever we make changes to a project.  

### **Pull Any Recent Changes from GitHub**  
```sh
git pull origin main
```

### **Modify Supplier Performance Data**  
- Update **supplier names, delivery times, and reliability scores** in the script (`utils_kiruthikaa.py`).  
- Modify the **formatted output (`byline` string)** to fit reporting needs.  

### **Stage, Commit & Push Changes**  
```sh
git add .
git commit -m "Updated supplier analytics module with reliability metrics"
git push origin main
```

---

## **Example Output (Supplier Performance Tracker)**
```
---------------------------------------------------------
Supplier Performance Analytics
---------------------------------------------------------
Total Suppliers:            15
Suppliers Meet Deadlines:   True
Average Defect Rate:        2.3%
Supplier Names:             ABC Logistics, Global Freight Co., Swift Supply Chain
Supplier Reliability Scores:[4.8, 3.9, 4.5, 4.2, 4.7]
Delivery Times (days):      [2, 3, 5, 4, 2, 7, 3]
Minimum Delivery Time:      2
Maximum Delivery Time:      7
Mean Delivery Time:         3.71
Standard Deviation:         1.93
```

---

## **Follow The Proven Path Provided**  
Carefully follow each step in order. If you run into challenges:  
- **Search the web for solutions.**  
- **Use AI assistants for explanations.**  
- **Experiment with code changes** (rename variables, log function calls, adjust parameters).  

---

## **CheatSheet: Commands to Manage Virtual Environment**  
For Windows PowerShell (adjust for Mac/Linux).  

```powershell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt
```

## **CheatSheet: Commands to Run Python Scripts**  
Activate your `.venv` and install dependencies before running Python files.  

```shell
python utils_kiruthikaa.py
python analyze_suppliers.py
python report_generator.py
```

## **CheatSheet: Git Workflow Commands**  
```shell
git add .
git commit -m "custom message"
git push origin main
```

---

### **Contributing**  
- Open issues or submit pull requests to enhance supplier tracking capabilities.  
- Contributions should follow best practices, including detailed commit messages.  

## Acknowledgements
Special Thanks To: 
- Dr.Case for her guidance and support
- Open Source Contributors for essential license and tools. 
---



