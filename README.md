# CryptoTracker

The Crypto Tracker Android App is a mobile application that allows users to track the prices and market trends of various cryptocurrencies. This app is designed to provide a simple and intuitive interface for users to stay up-to-date with the latest market information.

Features
This application provides the following features:

Track the prices and market trends of various cryptocurrencies in real-time.
Monitor the top gainers and losers of the day in the cryptocurrency market.


Architecture
This application follows the Model-View-ViewModel (MVVM) architectural pattern, which separates the application into three interconnected parts:

Models: Represent the data and the business logic of the application.
Views: Display the user interface and interact with the user.
ViewModels: Handle the user's requests, process the data, and return the response.
In this application, the models represent the cryptocurrencies, their prices, and market trends. The views are implemented with XML and use the Material Design guidelines for styling. The viewmodels handle the user's requests, process the data, and interact with the models to provide the appropriate response.

APIs
This application uses the following APIs to retrieve the data:

CoinMarketCap API: Provides the cryptocurrency prices, market trends, and historical data.
