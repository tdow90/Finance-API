how to get out of fiull screen # Finance-API

I asked ChatGPT to help me plan a project to work on to learn more about Backend dev and building an API, here is what it suggested and what Im going to build: 

Project Idea: Futures Portfolio Tracker with Market News Insights

Objective:
Create a RESTful API that allows users to track their futures investments. The API will fetch real-time futures prices using an external API and gather relevant market news articles using a web scraper. The goal is to give users insights into how their investments are performing and keep them updated with the latest news.

Features:

	1.	User Portfolio:
	•	Users can create, update, and delete a portfolio of futures contracts they own.
	•	Each portfolio entry will include the futures contract name, quantity, purchase price, and expiration date.
	2.	External API Integration:
	•	API to Use: You can use the Alpha Vantage API for real-time futures data. Alpha Vantage offers a wide range of financial data, including futures prices.
	•	Fetch real-time prices for the futures contracts in the user’s portfolio.
	•	Calculate the current value of the user’s portfolio by multiplying the quantity owned by the current price.
	3.	Web Scraper:
	•	Implement a web scraper to gather the latest market news articles related to the futures contracts in the user’s portfolio.
	•	The scraper could target popular financial news websites (e.g., Bloomberg, CNBC) and filter articles based on keywords related to the futures in the portfolio.
	4.	API Endpoints:
	•	/portfolio/ - List all portfolio entries and create a new entry.
	•	/portfolio/<id>/ - Retrieve, update, or delete a specific portfolio entry.
	•	/portfolio/<id>/value/ - Get the current value of the portfolio entry based on real-time prices.
	•	/portfolio/<id>/news/ - Get the latest market news articles related to the portfolio entry’s futures contract.
	5.	Calculations:
	•	Calculate the total value of the user’s entire futures portfolio.
	•	Calculate the percentage gain/loss for each futures contract based on the purchase price and current price.
	6.	Optional Enhancements:
	•	Implement user authentication so each user can manage their own portfolio.
	•	Add historical data tracking to show how the portfolio’s value has changed over time.
	•	Use Django Celery to schedule regular updates of futures prices and news articles.

Why This Project?

	•	Django and DRF: You’ll further develop your skills in creating APIs with Django and DRF, including handling external API requests.
	•	Web Scraping: You’ll gain experience in web scraping, including extracting and filtering data from financial news websites.
	•	Real-Time Data: You’ll learn how to integrate and process real-time data from external APIs, a valuable skill in many back-end projects.
	•	Database Calculations: You’ll perform calculations on your database objects to track and analyze portfolio performance.

Getting Started with Alpha Vantage API:

	•	API Key: You’ll need to sign up on the Alpha Vantage website to get an API key.
	•	Documentation: The Alpha Vantage API documentation provides detailed information on how to make requests for futures data.

This project would give you a strong foundation in integrating real-time financial data with Django while also offering a chance to work with web scraping and data analysis. Does this sound good to you?