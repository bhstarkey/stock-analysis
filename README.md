# 2018 and 2017 Stock Market Analysis

## Overview

The purpose for this analysis was to get a better understanding if the stock market in both 2017 and 2018, to help predict future trend lines for potential investments. Being able to look at previous returns, can help us choose which stocks would be most beneficial for us to invest in, as well as which ones would not be a good idea and could potentially lose us money. Looking at the returns for each stock gives us our answer.

## Analysis and Challenges

### Challenges with Coding
There were a couple challenges I faced with this analysis and the refactoring. Because of the structure of the variables as an array, and having to rotate through all of the variables there, I initially had issues setting up the for loops, and understanding that concept.

### Challenges with the Dataset
With the data, there are limitations because it only looks at 2 years. 2 years, in my opinion, does not give an accurate representation of the potential returns of a stock. The stock market is always fluctuating, and there are so many outside variables that affect it.

## Results

### Good Overall Stocks
Although 2018 was a rough year, there were 2 stocks that were positive for both years and stand out. ENPH and RUN both had over 80% return for 2018, and while not as high of a return for RUN in 2017, they both gave a return in 2017 as well. ENPH was 129.52% and RUN was 5.55%. Given that they were the only 2 that were positive both years, I think they would both be good options to invest in.

### Riskier Stocks to Consider
Depending on the investors, and how risk they are ok with being, there are 2 other options that also gave a return over the 2 years. Both DQ and SEDG, while negative for 2018, had an overall reurn of over 100% between the 2 years. GQ had roughly 137%, and SEDG ahd roughly 176%. With the stock market, there are some stocks such as these that may have some bad years, but if you're okay with riding those out, will still give you a good return when all things are said and done

![VBA_Challenge_2017_Output](https://user-images.githubusercontent.com/116474586/201488402-52811eb3-edb4-449d-9f66-97512ffb9a46.png)
![VBA_Challenge_2018_Output](https://user-images.githubusercontent.com/116474586/201488409-935bf0ac-5e4c-4862-ac68-e6fc43ab7f70.png)


### Refactoring Results
Refactoring the script definitely made a difference. Going from just under a second, to a tenth of a second makes a huge difference. The difference would be even greater when evaluating a larger set of data, and would be even more important then. While not a huge difference for the 12 stocks, it is definitely worth it if you're wanting to evaluate something as large as the whole stock market.

![VBA_Challenge_2018](https://user-images.githubusercontent.com/116474586/201488431-49759b0f-8010-4279-b598-8597e90c73af.png)
![VBA_Challenge_2018_Refactored](https://user-images.githubusercontent.com/116474586/201488435-4365685b-5aab-43b6-bdf5-3c26481e5dd8.png)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/116474586/201488441-edae537c-1669-4a5a-9d25-5a3292110fd6.png)
![VBA_Challenge_2017_Refactored](https://user-images.githubusercontent.com/116474586/201488442-79bfade8-7c4e-4937-9a1d-644321cea1a5.png)


## Summary

### Advantages of Refactoring
The advantages of refactoring code is that your code runs much more smoothly and efficiently. It pretty significantly cuts down on the run time, and allows you to have a gauge of your data much more instantaneously than when it isn't refactored.

### Disadvantages of Refactoring
There are cons though. You definitely have to know more about coding in order to refactor it. There were several issues that I ran into while refactoring, that I had to work through in order for it to run. It also takes a larger chunk of time to refactor it. Not only do you have to create the initial code, but then you nhave to go through and edit it so that it runs more efficiently.

### Conclusion
Overall though, I would say it is worth it to refactor the code, especially when you have a large dataset that you are needing to run analysis on.
