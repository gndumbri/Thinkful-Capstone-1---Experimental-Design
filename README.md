# Thinkful Capstone Experimental Design

This capstone was a project utilizing skills in experimental design, data analysis, and data visualization. In this project I reviewed a data set of about 22,000 records to look at college admission requirements among colleges and universities in 5 states (MI, OH, WI, IL, IN). 

I acquired this data set from the Education Data Explorer through the Urban Institute. 

I performed Exploratory Data Analysis using Python and corresponding packages: Matplotlib, Seaborn, Scipy, Pandas, and Numpy. 

I uncovered a difference between "merit based" (test scores) and "other" (personal essays, recommendations) finding a stronger correlation between "other" requirements and graduation rates. I found an r-value as high as 0.28 for graduation rates at 150% of normal time (in that case, 6 years to do 4 years, for example).

I then analyzed the difference among the 5 states and found a correlation as high as 0.32 in one state for "other" admission requirements and graduation rate. In all aforementioned pearson r-values, those numbers were significant with a p <<< 0.01.

The stastical methods I used in this analysis aside from the Pearson correlation, was Shapiro-Wilk for testing data distribution normality, Kruskal-Wallis for non-parametric comparison testing.

I visualized the data with histograms and swarm plots through matplotlib and seaborn respectively.

Folling this experiment I determined that merit based admission requirements could be less useful in determining students who will be successful (i.e. graduate) when compared to "other" admission requirements that may be more subjective and qualitative.
