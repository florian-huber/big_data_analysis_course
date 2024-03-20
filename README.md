# Material and tests for "Big Data Analysis" course
Course on big data analysis (code material and environment).
This course is given to 4th-semester DAISY (Data Science, AI, and Intelligent Systems) students at the University of Applied Sciences Düsseldorf (HSD).


## Create new environment for this course (recommended)
Creating a new environment for this course with many Python libraries that we will use in the Live Coding sessions is recommended. You can download the `environment.yml` file in this repository, or clone the repository using:
```
git clone https://github.com/florian-huber/big_data_analysis_course.git
```
Then, in the folder with the `environment.yml` file run:
```
conda env create -f environment.yml
```
This should create a Python 3.10 environment with the packages listed in the yaml-file.


## Tools used in the course
Numerous tools (or: libraries) will be used throughout this course.
1. Python libraries:
- The classics: Pandas, Numpy, Scipy, Matplotlib etc.
- For image handling: OpenCV
- For deep learning: PyTorch
- For databases: sqlite, annoy

2. Other tools:
- SQL (sqlite, postgres)
- neo4j
- Spark 
