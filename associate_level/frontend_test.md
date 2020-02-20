**Currency Conversion Front-End**

We have a simple API that returns a JSON array of currency version rates. 

An example of the API below :

GET [https://api.exchangeratesapi.io/latest](https://api.exchangeratesapi.io/latest)

The API will send a response in the format:

          {
            "base": "EUR",
            "date": "2018-04-08",
            "rates": {
              "CAD": 1.565,
              "CHF": 1.1798,
              "GBP": 0.87295,
              "SEK": 10.2983,
              "EUR": 1.092,
              "USD": 1.2234,
              ...
            }
          }

We would like you to use HTML, CSS and JavaScript to send a request to the API, read the API response, store the exchange rates, and propose an web interface to convert from GBP to USD using those stored exchange rates.

Feel free to use any frameworks (if any) you would like to achieve the task. Styling is not of importance.

You will be examined on:

- Asynchronous HTTP requests
- JavaScript best practices
- Test cases


Your code should be executable with no syntax errors, once complete, please zip your project and send it via email with instructions on how to run it.

If you have any questions regarding the test, please reach out to us.
