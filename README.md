# CS549-CourseProject
## Project Setup Guide

Follow the steps below to set up this project on your computer

### Prerequisites

- Python 3.7 or higher
- `git` installed on your computer

### Getting Started

#### 1. Clone the Repository

```bash
git clone https://github.com/ajsd05/CS549-CourseProject.git
cd CS549-CourseProject
```

#### 2. Create the Virtual Environment

On macOS/Linux
```bash
python -m venv venv
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
Download `kddcup.data_10_percent.gz` from: https://drive.google.com/file/d/1opkTRPvW9CjIDlFzV6jh5q_Nr4j75SMh/view?usp=drive_link 

Once the dataset is downloaded, place it in the `data/` folder.

