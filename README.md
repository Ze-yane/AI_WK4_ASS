# AI_WK4_ASS
This project applies machine learning techniques to the well-known Breast Cancer Wisconsin Dataset from Kaggle. The goal is to build an AI model that can automatically predict the priority level (High/Low) of a cancer diagnosis based on patient cell sample features.

---

## 📘 Overview
## 🧠 Task 1: AI-Powered Code Completion
### Objective:
Use an AI code assistant (e.g., GitHub Copilot or Tabnine) to generate a Python function that sorts a list of dictionaries by a specified key. Compare the AI-suggested version with a manually written one.


## 🤖 Task 2: Automated Testing with AI
### Objective:
Use **Selenium IDE** (or Testim.io) to automate login form testing for valid and invalid credentials.

### Test Flow:
1. Open `https://practicetestautomation.com/practice-test-login/`
2. Input credentials (valid & invalid)
3. Capture pass/fail results

**Example Test Cases:**
- ✅ Valid Login → “Logged In Successfully”
- ❌ Invalid Login → “Your username is invalid!”

**Summary (150 words):**
AI-assisted testing extends traditional automation by predicting edge cases and improving test coverage. Unlike manual testing, which can miss rare combinations, tools like Testim.io use machine learning to detect new UI states and dynamic elements automatically. This reduces flaky test failures and saves time maintaining scripts. The result is broader, faster, and more adaptive test coverage.

---

## 📊 Task 3: Predictive Analytics for Resource Allocation
### Objective:
Use the **Kaggle Breast Cancer Dataset** to train a model that predicts issue priority (High/Low).
This project uses **machine learning (Random Forest Classifier)** to predict whether a breast cancer case is high or low priority based on diagnostic data from Kaggle’s Breast Cancer dataset.

It demonstrates:
- Data cleaning and preprocessing
- Label encoding for classification
- Model training and evaluation
- Visualization of feature importance and confusion matrix

## ⚙️ Requirements
To run the notebook, install the following dependencies:

## ⚖️ Ethical Reflection
When deploying predictive models in organizations, **biases** in training data can affect fairness. For example, underrepresented patient groups might have less accurate predictions. Using fairness tools like **IBM AI Fairness 360**, such biases can be identified and mitigated. These tools measure disparate impact, equal opportunity, and help rebalance the dataset through reweighing or adversarial debiasing, ensuring equitable outcomes across all user groups.

## 💡 Bonus Task – Innovation Challenge
Proposal — SynthData Studio: An Intermediate AI-Assisted Test Data Synthesizer

Purpose
SynthData Studio creates realistic, constraint-aware synthetic datasets for testing and QA. It targets engineering teams that need representative test inputs (unit, integration, and performance) but lack privacy-safe or diverse production data. Unlike simple random generators, SynthData Studio enforces schema rules, inter-field constraints, and produces edge-case and adversarial inputs guided by code and usage patterns.

```bash
pip install pandas scikit-learn matplotlib seaborn


  


