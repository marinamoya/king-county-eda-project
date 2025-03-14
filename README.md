# King County EDA Project

## Project Overview
This project is an **Exploratory Data Analysis (EDA)** study conducted during my Weiterbildung in **Data Science, Machine Learning, and AI**. The goal is to analyze real estate data in King County to uncover insights and provide actionable recommendations for our client.

### Client Profile
| Name              | Role  | Investment Strategy  |
|------------------|------|---------------------|
| Erin Robinson   | Buyer | Invest in poor neighborhoods, buy & sell properties, recover costs + small profit, socially responsible |

## Deliverables
Through our EDA and statistical analysis, we have discovered the following key insights:
1. Through EDA/statistical analysis, come up with **at least 3 insights** regarding the overall data. One should be geographical.

3. In addition also come up with **at least 3 recommendations** for your client.

## Project Documentation
- **Context, feature description and other relevant information**: Located in the `documentation` folder.
- **Final presentation**: Available as a PDF in the repository.

</br>


# Setup
This repo contains a `requirements.txt` file with all necessary dependencies.

### **Prerequisites**
Before using **Plotly in Jupyter Lab**, ensure you have **Node.js** installed.

#### Check Node.js Version:
```sh
node -v
```
If Node.js is not installed, follow the steps below.

### Installation Instructions

#### **For macOS**
- **Step 1:** Update Homebrew and install Node.js
  ```sh
  brew update
  brew install node
  ```
- **Step 2:** Set up a virtual environment and install dependencies
  ```sh
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/bin/activate
  pip install --upgrade pip
  pip install -r requirements.txt
  ```

#### **For Windows**
- **Step 1:** Update Chocolatey and install Node.js
  ```sh
  choco upgrade chocolatey
  choco install nodejs
  ```
- **Step 2:** Set up a virtual environment and install dependencies
  - **For PowerShell:**
    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
  - **For Git Bash:**
    ```sh
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

#### **Note:**
If you encounter errors running `pip install --upgrade pip`, try:
```sh
python.exe -m pip install --upgrade pip
```

---

## License
This project is for educational purposes as part of a Weiterbildung program in **Data Science, Machine Learning, and AI**.

---

**Author:** [Marina Moya Sanchez]  
**Date:** [20-12-2025]