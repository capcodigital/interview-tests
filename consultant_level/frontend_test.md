**Currency Conversion Front-End**

We have set up simple API that returns a JSON array of currency version rates for a given input value in native currency. Assume for the sake of this, the native currency is GBP, upon sending a request amount to the AP will result in you receiving rates for USD and EUR.

An example of the API below.

The API is located at the below address:

[https://us-central1-ornate-apricot-220209.cloudfunctions.net/CodingTestFrontEnd-API](https://us-central1-ornate-apricot-220209.cloudfunctions.net/CodingTestFrontEnd-API)

It accepts a JSON request of the following format:

_{
          &quot;amount&quot;: &quot;1.434&quot;
}_

The API will send a response in the format:

_{
         &quot;USD&quot;: 1.87854,
         &quot;EUR&quot;: 1.6634399999999998
}_

We would like you to use HTML, CSS and JavaScript to send a request to the API, read the API response and display it in an organized way. In addition, you should add in some sort of sorting mechanic to the front-end. Feel free to use any frameworks (if any) you would like to achieve the task. Styling is not of importance.

You will be examined on:

- Asynchronous HTTP requests
- JavaScript best practices
- Test cases


Your code should be executable with no syntax errors, once complete, please zip your project and send it via email with instructions on how to run it.

If you have any questions regarding the test, please reach out to us.
