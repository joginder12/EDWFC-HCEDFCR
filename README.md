# Predicting drug‑resistant miRNAs in cancer (EDWFC-HCEDFCR)
                               Authors: Amrita Kundu, Joginder Singh, Shubhra Sankar Ray, and Jayanta Kumar Pal
                             E-Mail: joginder265@gmail.com and shubhra@isical.ac.in

## Download drug-resistant miRNA expression data from:
a)    For esophageal cancer data: - <a href = "https://drive.google.com/file/d/15bkTE8p5gpJkQmvlbcmhExbBi7ohHaPW/view">Esophageal_Cancer.csv </a>

b)    For lung cancer data: - <a href = "https://drive.google.com/file/d/1dIWvaRnXesxZU7STZ_zOvMZJmZKt4mBj/view">Lung_cancer.csv </a> 

## Steps to Run EDWFC-HCEDFCR
1. Open Python and install the packages **numpy**, **math**, **csv**, **pandas**, **sklearn**, **matplotlib**, **time**, **scipy**.  
(Use command `pip install package_name` e.g., `pip install pandas`.  
In higher versions of Python, use `pip3` in place of `pip`.)  
* In Windows environment, if **Spyder** is used for Python, then one has to install the **pip** package first using the command  
  `"python get-pip.py"`  

2. Download the code for **EDWFC** from: <a href = "https://drive.google.com/file/d/1Ry8wJ2t8EoNSHpHiKsOwagrMamGjEdza/view?usp=drive_link">`EDWFC.py` </a>  
3. Download the code for **HCEDFCR** from: <a href = "https://drive.google.com/file/d/1J1-MH4IGZsCSCWGYl6QXQXPeJU1HiqAc/view?usp=drive_link">`HCEDFCR.py` </a>    
   

4. Keep the code and the datasets in the same folder, otherwise change the folder path along with the name of the dataset in the code (**Line number 3 and 4** in **EDWFC** and **Line number 10 and 11** in **HCEDFCR**).  

5. Run `EDWFC.py` and `HCEDFCR.py` to produce `EDWFC_results.csv` and `HCERDFCR_results.csv` and `EDWFC_performance.csv`.  
   - `EDWFC_results.csv` contains the ranked list of **miRNA**.
   - `HCEDFCR_results.csv` contains the cluster ranks and ranked list of **miRNA**. 

## Related Article
Kundu, A., Singh, J., Pal, J. K., & Ray, S. S. (2022). Predicting drug-resistant miRNAs in cancer. Network Modeling Analysis in Health Informatics and Bioinformatics, 12(1), 6.

