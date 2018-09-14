# sicchallenge
# ISSA # Intelligent SIAML Service Agent

# ISSA is an intelligent machine learning chat bot. To get access to test ISSA and her capabilities please copy and paste this link in your browser or click https://portal.azure.com

# After that enter the following login details:
#Email Address: osasighodalo@outlook.com
#Password: theresa1

# When you have been granted access, navigate to 'Test in Web Chat' under Bot management and communicate with ISSA
# If you cannot get access, please call or email me +234-9036813408 (osasighodalo@gmail.com), thanks!

# ISSA is capable of answering concerns regarding opening an account, redemption requests, risk and return questions, minimum tenor, initial investment, SIAML account numbers, SIAML contact information, SIAML mutual funds definitions and functions and others.

# Please view the report below as it contains other aspects of the solution. A complete and better version of the report with graphical visualizations will be provided upon request.



STANBIC IBTC INNOVATION CHALLENGE
FRONTWATER-TECH & DEVELOPMENT VENTURES NIG. LTD.
SEPTEMBER, 2018


 
	INTRODUCTION
	THE PROBLEM
The problem this report sets out to solve is that of efficiently utilizing Stanbic IBTC Asset Management Limited’s (SIAML) analytical resources to increase its customer engagement and acquisition and ultimately its revenue.

	THE SOLUTION
To achieve a solution, we broke down the problem into three (3) categories and addressed them independently. However, the goal was to arrive at a solution that meets the needs of SIAML as well as its customers.
The 3 key areas addressed are:
 
Since Stanbic IBTC is a financial institution that is committed to its customers and ensuring it meets their end-to-end financial needs, we felt improving customer experience will help strengthen existing relationships with customers as well as build new ones. We tackled this by building an intelligent machine learning bot (Issa), designed on the Microsoft Azure cloud platform.

Issa is a unique, one-of-a-kind intelligent web bot designed specifically for SIAML business operations. She is robust and versatile, and has the ability to constantly learn as she interacts with all SIAML customers, both existing and new.  She is equipped to handle and respond to customers FAQs regarding SIAML mutual funds.

Issa can be connected to multiple channels where SIAML customers are interacting online such as Facebook Messenger, Skype, Email, etc.
Please note that she is still in production stage, as such, there may be some glitches in the accuracy of the responses she is able to provide.

A link to the demo page has been attached to this application. Issa can be queried for questions concerning investing in SIAML mutual funds, as well as others regarding risk, return, initial investment, opening an account, contact information, purchasing units, minimum tenor, fund definitions and functions, transaction fees, SIAML account numbers, redemption requests and more.

The second aspect of the solution, which this report focuses on, is in improving SIAML’s ability to statistically identify profitable opportunities in the market using analytics and superior information about securities to derive higher returns.

We utilized the mean-variance analysis and the Sharpe ratio measure to assess the performance of eight (8) mutual funds from January to December 2016. The mutual funds considered are: Stanbic IBTC Balanced Fund, Stanbic IBTC Bond Fund, Stanbic IBTC ETF 30, Stanbic IBTC Ethical Fund, Stanbic IBTC Guaranteed Investment Fund, Stanbic Imaan Balanced Fund, Stanbic IBTC Money Market Fund, and Stanbic IBTC Nigerian Equity Fund.

We believe that SIAML’s ability to increase customer acquisition, continually add value to unit-holders, and ensure meaningful returns is hinged on its capability to effectively manage the combined risk of its portfolio. The evidence from our work indicates that the 8 mutual funds reviewed in the year 2016 were not able to predict stock prices well enough to outperform the benchmark 2016 average risk-free return rate.

The final part of the solution involves implementing a strategy to target specific demographics of people in order to utilize marketing resources effectively whilst connecting with SIAML target market. This approach involves adopting techniques such as frequent cold calling, emailing, as well as making daily visits to potential target customers (individuals & institutions). The details of this approach are discussed below.

	THE MODEL
This analysis utilizes the Sharpe ratio to analyze the performance of 8 mutual funds offered by SIAML in the year 2016.

	THE SHARPE RATIO
Sharpe ratio (SR) is the ratio of the excess expected return of an investment to its return volatility or standard deviation. 
SR = (μ- R_f)/σ
Where μ is the average return for the period under review,  σ  is the standard deviation, and the excess expected return is usually computed relative to the risk-free rate, Rf. 

	THE PROCEDURE
The dataset was compiled from archives of daily return entries of 8 SIAML mutual funds found on the website of Fund Managers Association of Nigeria. The risk free rate chosen for the purpose of our work is the average true yield rate (June 2016) of the one (1) year Nigerian Treasury Bill (NTB), as found on the website of the Central Bank of Nigeria (CBN), which was 13.05%. The S&P/FMDQ Nigerian Sovereign Bond Index (NGN) as at July 1, 2016, stood at 13.11%, as such our choice was validated. 

First we derived the averages of the individual funds, then the variances, standard deviation and finally the Sharpe ratio.

	THE DATA AND RESULTS
The following table of figures represents the results of our analysis of the individual mutual funds for the year 2016.
Fund Name	Average Return (Mean) %	Variance (σ^2) %	Standard Deviation (σ) %	Sharpe Ratio (SR) 
Stanbic IBTC Balanced Fund	3.205607	19.606529	4.427926	-2.223251
Stanbic IBTC Bond Fund	0.210289	5.414621	2.326934	-5.517867
Stanbic IBTC ETF 30	-7.890087	45.794552	6.767167	-3.094365
StanbicIBTC Ethical Fund	1.017746	29.783295	5.457407	-2.204756
Stanbic IBTC Guaranteed Investment Fund	4.238671	7.811930	2.794983	-3.152552
Stanbic IBTC Imaan Fund	-2.964509	8.024913	2.832828	-5.653188
Stanbic IBTC Money Market Fund	10.656069	16.591339	4.073247	-0.587721
Stanbic IBTC Nigerian Equity Fund	0.956301	47.432599	6.887133	-1.755985

The graph below represents the average return of the individual funds:		

 

Figure 1.	The Average Return of 8 SIAML Mutual Funds in 2016.
In the analysis conducted for the year 2016, the Stanbic IBTC Money Market Fund seemed to be the most rewarding giving average returns of about 10.66%, and the worst performing fund was the in the same period was the Stanbic IBTC ETF 30, offering an average loss return of -7.89%.  However, average return provides only a snapshot of the individual investment's performance and does not give investors any indication of its volatility. 

The portfolio’s volatility is observed from the standard deviation. High standard deviation equals high risk of the particular investment fund. Our analysis shows that in the year 2016 the mutual funds with the lowest risk profile were Stanbic IBTC Bond Fund, Stanbic IBTC Guaranteed Investment Fund, and Stanbic IBTC Imaan Fund with standard deviations of 2,33%, 2.79%, and 2.83% respectively. Those with the most volatility were Stanbic IBTC Nigerian Equity Fund, and Stanbic IBTC ETF 30 with 6.89% and 6.77% respectively.

Therefore, although the Stanbic IBTC ETF 30 provided the best average yield for the year, it was much more volatile than some of the other low performing funds, hence more risky. This information supports the Fund manager to reconsider trading strategy to improve selection of stocks moving forward thus improving leverage to reinvest, and providing more dividends to unit-holders.
The graph below is a representation of the volatility of the individual funds under review:
  
Figure 2.	The Volatility/ Risk (Std. dev.) of the underlying SIAML Mutual Funds in 2016.

The Sharpe ratio is a measure of the Fund manager’s ability to get leverage from the market and reinvest the cash in the trading strategy employed. A positive Sharpe ratio is hence the measure of the Fund manger’s skill, which is benchmarked against the market index and the risk free rate within the period under review.  A negative Sharpe ratio means the Fund manager has performed worse than say for instance if one held the NSE All Share Index in a rising market.

From our analysis, none of the 8 SIAML mutual funds generated a positive Sharpe ratio in 2016. The best Sharpe ratio score was observed in the Stanbic IBTC Money Market Fund at about -0.59 while the worst performers were the Stanbic IBTC Imaan Fund and the Stanbic IBTC Bond Fund with Sharpe ratios of -5.65 and -5.52 respectively.
The following graph shows the distribution of the Sharpe ratio values of the 8 mutual funds under review:
 
Figure 3.	The Sharpe Ratio of the 8 SIAML Mutual Funds in 2016.

	TARGET MARKETING
We are of the opinion that more conscious effort needs to be put into this space. Potential investors may have extra money saved up somewhere but do not know how to invest it. Even when people are thinking of getting into investing, many still need to be convinced and reminded of the benefits they are potentially missing out on. To this effect, we developed the Five-on-Five Target Marketing Plan. 

This plan entails:
	Assigning at least 5 top-selling representatives of the Fund manager to visit at least 5 target firms a day each (50 visits a week for 10 representatives) where potential investors may be.
	
	Committing at least 5 other representatives to dedicating the hours of 9:00 AM to 11:00 AM and 1:00 PM to 4:00 PM (5 hours total) to cold calling and emailing potential investors and leads gotten from all SIAML channels and sources.
	
	These representatives are to acquire and possibly convert at least 5 leads a week from targeting high net-worth and business individuals in certain places such as airports, hotels, and fancy restaurants, targeting groups such as residential estate associations in the urban areas of Ikoyi, Victoria Island, and Lekki axis (a good number of residential estate associations have meetings on the last Saturday of the month), and also institutions such as churches.
	
	Hosting at least 5 social and awareness events a year where potential customers get to connect with the company and more importantly with successful existing investors who can share their success stories and experience.

	CONCLUSION
This report set out to present solutions to the problem of efficiently utilizing powerful data analytics to solve the problem of customer engagement and acquisition for SIAML. To achieve this, we at FDV Nig. Ltd. broke down the challenge into 3 categories and we are ready to further implement each of them to improve SIAML operations and its customers’ experience. The 3 solution categories focuses on using analytics, statistical capability and artificial intelligence to improve upon:
	Customer Experience
	Fund Performance
	Target Marketing
  
To address the category of customer experience and engagement we designed and developed a state-of-the-art intelligent machine learning bot called Issa, which is already functional to some degree and awaiting to be launched and connected to SIAML web channels.

We are technically positioned to offer high statistical and analytical capabilities in effectively managing the combined risks of SIAML mutual funds portfolio, thereby increasing leverage for SIAML to invest more money in the market and add more value (meaningful returns) to its existing and potential unit-holders. Future work will include expanding sample size for analysis from 1 year to 5 or 10 years whilst including predictive modeling based on SIAML existing customer data. Also other risk management measures such as Jensen Alpha model, Treynor ratio, Minimum Conditional Value-at-Risk (CVAR) Portfolio Approach will be utilized when conducting future analysis and implementation of the solution.

Finally, we recognized the need for marketing and developed the Five-on-Five Target Marketing Plan to serve as basic starting point for our target marketing strategy, which will be further evaluated and improved upon in the implementation phase of the solution.



