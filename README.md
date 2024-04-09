# RealTime Stock Price Tracker and Predictor

Welcome to the **RealTime Stock Price Tracker and Predictor** project, my latest creation born out of a playful exploration of web scraping and real-time analysis concepts! This light-hearted yet powerful tool is designed to keep you updated with real-time financial market trends, specifically focusing on stock price movements. It's like having a financial market radar that operates right from your command line, offering insights into how stocks are performing at any given moment.

## How It Works
Our project is built around several key components that work together to fetch, analyze, and display stock price data:

* **DataFetcher**: This is where the magic begins. Given a URL, this class reaches out to the internet with its digital tentacles to grab the latest stock price data. Thanks to this, we can keep our analysis fresh and timely.

* **PriceParser**: Once we have the data, it's not immediately ready to be analyzed. This class takes the raw HTML content fetched by our DataFetcher and extracts the precise pieces of information we need: the stock prices.

* **Metrics**: What's data without analysis? The Metrics class is our mathematical wizard, calculating various statistical measures to evaluate the performance of stocks over time. From mean absolute error to root mean square error, it gives us a comprehensive view of market trends.

* **AutoRegressionModel**: This is where things get predictive. Using the historical stock price data, this class employs an AutoRegression model to forecast future price movements. It’s like a crystal ball, but grounded in statistical science.

* **MainLoop**: The heartbeat of our application, this class orchestrates the entire process. It continuously fetches new data, parses it, updates our dataset, and uses the model to predict and display future trends. It's what keeps the project alive and kicking, providing endless insights.

## Why This Project?
In the ever-changing landscape of financial markets, having up-to-date information is crucial for making informed decisions. Whether you're a seasoned investor or just curious about how stock prices move, this project offers a window into the world of financial markets. It's a blend of real-time data fetching, predictive modeling, and data visualization, all wrapped up in a user-friendly package.

So, dive in, explore the code, and see what insights you can uncover with our Market Trend Analyzer. Whether you're tracking the giants of the tech world or keeping an eye on emerging startups, this tool is here to keep you informed and ahead of the curve.

### Happy analyzing!

_**PS**: Please note that the American stock market operates from 15:30 to 22:00 (Central European Summer Time). If you run this program outside these hours, it will operate on the last available price data since the market will be closed._
