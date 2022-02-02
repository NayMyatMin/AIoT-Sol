# AIoT-Sol

Python 3.9 was used to create the application files. 

| Library | Task |
| ------ | ------ |
|[ Sklearn ](http://scikit-learn.org/stable/install.html)| Machine Learning Library|
| [ Numpy ](http://www.numpy.org/) |Mathematical Operations|
| [ Pandas  ](https://pandas.pydata.org/pandas-docs/stable/install.html)|  Data Analysis Tools |
| [ Matplotlib ](https://matplotlib.org/users/installing.html) |Graphics and Visuality|

The implementation phase consists of 5 steps, which are:
1-	Pre-processing
2-	Statistics
3-	Attack Filtering
4-	Feature Selection
5-	Machine Learning Implementation

Each of these steps contains one or more Python files. The same file was saved with both "py" and "ipynb" extensions. The code they contain is exactly the same. The file with the ipynb extension has the advantage of saving the state of the last run of that file and the screen output.

Thus, screen output can be seen without re-running the files. Files with the ipynb extension can be run using the [jupyter notebook](http://jupyter.org/install) program. When running the codes, the sequence numbers in the filenames should be followed.

The attack categories are as follows:
1)	Network Attacks: automated vulnerability scanning, network scanning, network logon brute-force, man-in-the-middle attack and pppd remote code execution.
2)	Denial-of-Service Attacks: SYN Flood, SSDP Flood, and SSL Regeneration.
3)	Server-side Web Attacks: SQL Injection, Command Injection, Server-side Request Forgery, Open Redirect and XML External Injection.
4)	Client-side Web Attacks: Cross-site Scripting, and Cross-site Request Forgery.
5)	Web IoT Message Protocol Attack: MQTT Brute-force.

Because the output of almost every program is the prerequisite for the operation of the next program. Each step is described in detail below.

For this program to work, the dataset ([AIoT-Sol Dataset]) files must be in the "CSVs" folder in the same location as the program. The dataset files can be access [ here ](https://drive.google.com/file/d/1IDfYy5JgSK2U87hXOhkR7-C782A0cjdS/view?usp=sharing).  (The reason that these files are given an external link is that the maximum limit of the file in the cseegit system is 10 MB)

As a result of executing this file, a file named "all_data.csv" is created. This file is a prerequisite for the other steps to work.
