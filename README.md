# frt_project

<h1> Predictive analysis for cryptocurrency investment </h1>

<h2> Project Statement/Opportunity </h3>

<p>In this project we will be determining if investing in cryptocurrency and holding that investment for long term is beneficial for the investor or not. Here we will observe the past trends of different currencies that include their open, high, low and close alongside the time period in date format. Then we shall be performing predictive analysis for the investment decision and visualise it through a dashboard using PowerBI.</p>

<h2> Azure Technologies Used </h3>

<b> 1. PowerBI embedded </b> <br>
<b> 2. Static WebApp  </b> <br>
<b> 3. Azure Virtual Machines </b>

<h2> Prerequisites </h3>

<b> 1. Azure Subscription </b><br>
<b> 2. Python </b>

<h2> Project Description </h2>

<p> The goal for this project is analysing if long term investment and holding those are worth the wait considering the immense crashes and risk of being a part of new fangled mode of investment. Observing the current Return of Investment and historic trends on investing in cryptocurrencies our project will determine if you shall be holding the money in one a diversified set of coins or in a limited number of strong cryptocurrency projects. We shall also be laying down a dashboard which will let you select low return and low risk coins vs high return and high risk coins. </p>

<h2> Proposed Methodology </h2>
<p> Using the dataset from Kaggle for historic prices of top 100 cryptocurrency coins for exploratory data analysis using tools provided by MicrosoL azure. Later on using Power BI for visualisation of the desired results. We are using Power BI because the solu6on comprises several products and services, and value and versatility comes from leveraging the individual elements, and taking advantage of how they work together. Hence making the predictive conclusion will be easier and
accurate as user point of view. </p>

<h2> About the DataSet </h2>
<p>The dataset is a Zip file that consists of the crypto prices of nearly 75 coins from their start date till 30/11/2021. A leaderboard file as of 30/11/2021 has also been included in the zip file named Current Crypto Leaderboard.csv, which has the market capitalization, rank, coin name, symbol, Price, and a tagging variable that mentions the availability of the corresponding coin in the dataset. Historical data(day-interval) of all the coins mentioned in the leaderboard is provided in the dataset. The leaderboard is subject to change as the market cap increases/decreases. Any new coin which enters the top 100 will be added to the dataset. The leaderboard and the dataset will be updated on a monthly basis.</p>

<img width="716" alt="Screenshot 2022-07-13 at 11 46 07 PM" src="https://user-images.githubusercontent.com/58964309/178824748-bcfaa0bb-d6e8-4002-8657-7a2389172dc2.png">



<p> The name column contains the actual name of the coin</p> <br>
<p> The symbol column contains the symbol of the coin </p> <br>
<p> The high column contains the highest price that particular coin has reached</p> <br>
<p> The low column contains the lowest price that particular coin has reached</p> <br>
<p> The open column contains the at what price the market opened</p> <br>
<p>The close column contains the at what price the market closed</p> <br>
<p> The volume column contains how much the given cryptocurrency has traded over a period of time</p> <br>
<p> The marketcap column contains what is the marketcap at that particular date and time for the listed crypto</p> <br>

<h2> Exploratory Data Analysis </h2>
<p> We have used Google Colab with python for EDA of the dataset. We used pandas, numpy, matplotlib.pyplot, seaborn, pandas_datareader.data  plotly.express, and plotly.graph_objects. Pandas is mainly used for data analysis and associated manipulation of tabular data in Dataframes.NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices. </p>


<img width="1125" alt="Screenshot 2022-07-14 at 1 27 13 AM" src="https://user-images.githubusercontent.com/58964309/178824964-c6b2b111-243a-41bc-83f2-57e5af401400.png">

</p> In this cell we have plotted the marketcap of top 5 coins </p>
<img width="1226" alt="Screenshot 2022-07-14 at 1 27 56 AM" src="https://user-images.githubusercontent.com/58964309/178824988-b6cc5b80-d600-4697-8a5c-88649b29a716.png">
</p> In this cell we have plotted the closing price of top 4 coins in a line chart</p>


<img width="1226" alt="Screenshot 2022-07-14 at 1 28 09 AM" src="https://user-images.githubusercontent.com/58964309/178825023-300587d8-cfb1-4590-b04f-dc03f2db6a6b.png">
</p> In this cell we have plotted the closing price of top 4 coins in a line chart excluding BTC and ETH and USDT in the last graph </p>

<img width="1356" alt="Screenshot 2022-07-14 at 1 28 30 AM" src="https://user-images.githubusercontent.com/58964309/178825114-c626eb7c-05d3-43f3-8dcd-77c0c7060831.png">
</p> In this cell we have plotted the prices of differnet coins in line chart </p>


<img width="1356" alt="Screenshot 2022-07-14 at 1 28 43 AM" src="https://user-images.githubusercontent.com/58964309/178825140-4c94d54f-8de6-4d9f-a6de-b15e92e70ee4.png">
</p> In this cell we have plotted the moving average coins to determine the sentiments of market </p>


<img width="1356" alt="Screenshot 2022-07-14 at 1 29 00 AM" src="https://user-images.githubusercontent.com/58964309/178825153-8b227f8f-18a5-4f21-bd26-ce6b58ab8611.png">
</p> In this cell we have plotted the area graph </p>

<img width="1356" alt="Screenshot 2022-07-14 at 1 29 11 AM" src="https://user-images.githubusercontent.com/58964309/178825213-0395f878-4655-49cf-8c4a-a8aaf2f76d17.png">

</p> In this cell we have plotted area graph for market cap of all the coins </p>
</p> To learn more about the EDA kindly refer the python file in the repo </p>

<h2> Visualization of DataSet on PowerBI </h2>
<p> Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data. PowerBI is a tool viz tool provided by microsoft, it enables us to create intercative dashboards and help us to gain insights out of data to make informed decisions. In out case informed decision in investment. </p>

<img width="1238" alt="Screenshot 2022-07-14 at 1 31 04 AM" src="https://user-images.githubusercontent.com/58964309/178828029-ebef43e0-62c8-49b9-ac69-30ef36fa4117.png">

<img width="1238" alt="Screenshot 2022-07-14 at 1 31 12 AM" src="https://user-images.githubusercontent.com/58964309/178828066-3c3dcf8b-58af-4fbc-a0a6-d43eb3ab334c.png">

<img width="1238" alt="Screenshot 2022-07-14 at 1 31 19 AM" src="https://user-images.githubusercontent.com/58964309/178828090-ff086daf-70ab-470c-9cfd-4fe6dba35bcb.png">

<p> Above are few snapshots from the dashboards we have created in PowerBI, please click on the link we have provided to get interact with the Dashboard and read the insights. </p>




