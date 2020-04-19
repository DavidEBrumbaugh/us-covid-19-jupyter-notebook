# us-covid-19-jupyter-notebook
Forecast of Covid 19 cases using Covid Tracking Project and Jupyter Notebook

# Overview:  
This is a forecast of US covid-19 infections base on current national data and the assumption that the virus will
follow a logistic curve.

## For background see: 
*Exponential growth and epidemics*  
3Blue1Brown  
https://youtu.be/Kas0tIxDvrg for the basic math.[1]

*The Mathematics Behind the Coronavirus Spread*  
By Stu Schwartz, www.MasterMathMentor.com  
http://www.mastermathmentor.com/mmm-archive/CoronaVirus.pdf [2]  

The conclusion from both of the above references is that historially viruses follow a logistic curve.  
Page 8 of Schwartz[2]  implies that the general formula for logistic curves for viral growth is:  
cases = capacity / (1+p1*(e^(p2*day))

So the idea here  is to solve for capacity, p1 and p2 using curve fitting.

capacity is the theortical maximum number of infections.

## Data Sources
Covid Tracking Project: https://covidtracking.com/  
American Hospital Association: https://www.aha.org/statistics/fast-facts-us-hospitals  

## Credit
This code borrows heavily from:  
https://github.com/KentShikama/covid19-curve-fitting#hackathon-quality-curve-fitting-for-us-covid19-cases 

## License
MIT License  

## Author
David Brumbaugh

