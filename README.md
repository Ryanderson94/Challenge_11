# Search Traffic Financial Analysis and Forecast

This analysis reivews Mercado Libre, a South American e-commerce company. Using Google Colab, we aim to see if the ability to predict search traffic can translate into the ability to successfully trade the stock. The analysis is divided into five parts:
1. Find unusual patterns in hourly Google search traffic
- In part 1 we find that Google search traffic increased during the month that MErcadoLibre released its financial results. 
2. Mining search traffic data for seasonality
- In part 2, we can see that search traffih is concentrated between the hours of 23:00 and 02:00 each day.
3. Relating search traffic to stock price patterns
- In part 3 we see that there is a correlation among search trends and close prices. Morever, there is a negative correlation between search traffic and stock volatility and a positive relationship between search restuls and hourly stock return. 
4. Creating time series model with Prophet
- In part 4, using the Prophet functions, we see that 1am is the most popular time of day for search terms, Tuesday is the most popular day and October is the low point for all search traffic. 
5. Forecasting revenue using time-series models
- IN part 5 we see that peak revenue days are Wednesdays and Mercado's expected sales for the next quarter are 2163.

After each section, there are questions and answers to ensure comprehension of the material 

# Technologies

This program leverages python 3.7+

To ensure all dependencies are installed and up-to-date, please run the following commands in your terminal once you have cloned the repository to your local machine.
run pip install -r requirements.txt

---

## Installation Guide

1. Copy this repository via the URL (SSH or HTTP)
<img width="907" alt="Screen Shot 2022-04-03 at 3 35 27 PM" src="https://user-images.githubusercontent.com/98444459/161445246-d4eecac4-44ae-452f-8e0c-ebaa9e523908.png">

2. Run a git clone command in your terminal or git bash under the desired local directory
<img width="689" alt="Screen Shot 2022-05-25 at 1 39 17 AM" src="https://user-images.githubusercontent.com/98444459/170187991-6383aedf-cc47-4550-97f8-54262253043e.png">

3. If you receive errors, please review the dependencies above, install them and try again. 

---

## Usage

1. Open Google Colab at colab.research.google.com

2. When prompted to create a new notebook or load a file, click the upload tab and select the forecasting_net_prophet.ipnyb file.
<img width="852" alt="Screen Shot 2022-06-05 at 7 31 20 PM" src="https://user-images.githubusercontent.com/98444459/172075112-667a4d2c-bf6c-4c4c-9a27-1a3766dae642.png">

3. Follow the detailed instructions within the notebook file. 

---

## Contributors

Made by:
Ryan Anderson
  Email: m.anderson.ryan@gmail.com
  LinkedIn: https://www.linkedin.com/in/ryan-anderson-57b2b173

---

## License

No licenses are required to run this application
