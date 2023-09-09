# InternSavy_Task3_CurrencyConverter
Internsavy Internship Task 3
# ITS DEVELOPED USING JAVA PROGRAMMING LANGUAGE USING NETBEANS IDE UNDER LINUX OS
The currency converter Java based project encapsulates currency conversion functionality by fetching the latest exchange rates from an API using a specified API key. 
It initializes an object by establishing an HTTP connection to the API, parsing the JSON response to extract currency rates, and storing them in a `JSONObject`. 
The `getExchange` method within the class facilitates currency conversion, taking an amount, source currency code, and target currency code as parameters. 
It calculates the converted amount accurately by applying the exchange rates and ensures a two-decimal-place format using `DecimalFormat`. 
This project is a handy tool for developers looking to perform real-time currency conversions in their applications while leveraging external exchange rate data. 
It's important to note that using an API requires a valid API key, 
and developers should be mindful of any usage limitations and terms of service associated with the chosen API.
