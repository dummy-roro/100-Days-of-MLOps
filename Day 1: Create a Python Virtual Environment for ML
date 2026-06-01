#Day 1: Create a Python Virtual Environment for ML

The xFusionCorp Industries ML team uses uv and lockfiles to keep Python dependencies reproducible across machines. A teammate has left behind a requirements.in specification that does not match the team's standard. Correct it and compile it into a pinned lockfile. 

A high-level dependency specification exists at /root/code/fraud-detection/requirements.in. uv is already installed. 

The corrected specification must meet the following requirements: 

it lists exactly these four top-level packages: scikit-learn, mlflow, pandas, and numpy; 
every package carries a version constraint that uv can actually satisfy against PyPI. 
Review the existing requirements.in, and correct everything that does not match the requirements above. 

From the project directory, compile the corrected specification into a pinned lockfile: 

uv pip compile requirements.in -o requirements.txt 

The resulting requirements.txt must pin each of the four top-level packages to an exact version using ==, and must also include the transitive dependencies that uv resolved.

#Solution
Create virtual environment in ml-env.
```bash
python3 -m venv ml-env
```
Activate enviornment, then install ML packages.
```bash
source ml-env/bin/activate
pip install numpy pandas scikit-learn matplotlib
```
Freeze installed packages into requirements.txt
```bash
pip freeze > requirements.txt
```
To test run the following command
```bash
pip install -r requirements.txt
```
