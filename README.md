# Emergency 911 Calls - Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.7.6-blue) ![License](https://img.shields.io/badge/License-Apache%202.0-orange) ![Contributions](https://img.shields.io/badge/Contributions-Welcome-green)

In this notebook we analyze a dataset call [Emergency - 911 Calls](https://www.kaggle.com/mchirico/montcoalert), which you can find in Kaggle.

One of the objectives of this notebook is to show step-by-step how to analyze and visualize the dataset to better understand 911 calls and what originates them. Moreover, we are going to explain most of the concepts used so that you understand why we are using them.

To see the Kernel directly from Kaggle click [here.](https://www.kaggle.com/tomasmantero/emergency-911-calls-exploratory-data-analysis)

This dataset contains emergency calls from Montgomery County, PA. It includes calls from 2015 to 2020.

***Feature Columns***

* **lat:** String variable, Latitude
* **lng:** String variable, Longitude
* **desc:** String variable, Description of the Emergency Call
* **zip:** String variable, ZIP Code
* **title:** String variable, Title of Emergency
* **timeStamp:** String variable, Date and time of the call, YYYY-MM-DD HH:MM:SS
* **twp:** String variable, Township
* **addr:** String variable, General Address
* **e:** String variable, Dummy variable, Index column (always 1)

***Montgomery County***

Montgomery County, locally also referred to as Montco, is a county located in the Commonwealth of Pennsylvania. As of the 2010 census, the population was 799,874, making it the third-most populous county in Pennsylvania, after Philadelphia and Allegheny Counties. The county seat is Norristown. Montgomery County is very diverse, ranging from farms and open land in Upper Hanover to densely populated rowhouse streets in Cheltenham.

***911 Calls***

Created by Congress in 2004 as the 911 Implementation and Coordination Office (ICO), the National 911 Program is housed within the National Highway Traffic Safety Administration at the U.S. Department of Transportation and is a joint program with the National Telecommunication and Information Administration in the Department of Commerce.

The following questions will be answered throughout the Kernel:

* **Which features are available in the dataset?**
* **How many rows and columns does the dataset have?**
* **Which features are categorical?**
* **Which features are numerical?**
* **Which features contain blank, null or empty values?**
* **What are the data types for various features?**
* **How many zip codes does the dataset have?**
* **What are the top 5 zip codes for 911 calls?**
* **What are the top 5 townships (twp) for 911 calls?**
* **How many unique title of emergency codes are there?**
* **What is the most common Reason for a 911 call based off of this new column?**

## License

This Notebook has been released under the Apache 2.0 open source license.
