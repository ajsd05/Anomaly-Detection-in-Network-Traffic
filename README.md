# Anomaly Detection in Network Traffic
This project aims to develop machine learning pipelines that aid in detecting network
anomalies/attacks by creating a predictive model that distinguishes the “bad” connections
from “good” connections. This is done through data preprocessing, implementation of
several machine learning algorithms, and comprehensive evaluation of said models.
## Project Setup Guide

Follow the steps below to set up this project on your computer

### Prerequisites

- Python 3.7 or higher
- `git` installed on your computer

### Getting Started

*If viewing from GitHub, start at step 1, if not, proceed to step 2*
#### 1. Clone the Repository

```bash
git clone https://github.com/ajsd05/CS549-CourseProject.git
cd CS549-CourseProject
```

#### 2. Create the Virtual Environment

On macOS/Linux
```bash
python -m venv venv
python3 -m venv venv # if python3 is command propmt for python
```


On Windows
```cmd
venv\Scripts\activate
```

#### 3. Activate the Virtual Environment
```bash
source venv/bin/activate
```

#### 4. Install Dependencies

Once the virtual environment is active, install the required packages:
```bash
pip install -r requirements.txt
```
#### 5. Install the dataset
**If dataset is not in data/ folder then complete steps below**

Download `kddcup.data_10_percent.gz` from: https://drive.google.com/file/d/1opkTRPvW9CjIDlFzV6jh5q_Nr4j75SMh/view?usp=drive_link 

Once the dataset is downloaded, place it in the `data/` folder.

#### 6. Open Jupyter Notebook and access the project file
After the virtual environment is activated:
```bash
jupyter notebook
```
Then open **CS549Project.ipynb** to access the project code.
#### 7. Run the code
Once the notebook is open run all the cells to view the results.

