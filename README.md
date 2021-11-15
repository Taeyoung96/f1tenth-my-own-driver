# F1tenth My own driver  

Midterm project for 2021 Fall Robot Navigation lecture

## Development environment 
|Language|OS|  
|:---:|:---:|  
|Python|Ubuntu 18.04|  

You could make same enviromnet using Anaconda.  
```
conda create -n f1tenth python=3.8  
conda activate f1tenth  
pip install -r requirements.txt  
```

Baseline code can be found at [F1Tenth Riders Quickstart](https://gitlab.com/acrome-colab/riders-poc/f1tenth-riders-quickstart).  
I improved Gap-follower algorithm. Gap-follower algorithm is one of the reactive method for planning.  
If you want to know more about Gap-follower algorithm, click [this link](https://f1tenth-coursekit.readthedocs.io/en/stable/lectures/ModuleB/lecture06.html#doc-lecture06).  

I make a look-up table for velocity, so this table makes Gap-follower algorithm faster.  
My own driver is in `pkg/src/pkg/drivers.py`.  

## Result  
|Map|Lab time|Rank|  
|:---:|:---:|:---:|   
|SOCHI|84.08|#5|  
|SILVERSTONE|78.4|#7|  

