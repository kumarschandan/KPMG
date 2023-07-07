In this code snippet, we use the requests library to send a GET request to the IMDS endpoint URL. The Metadata: true header is included to indicate that we want to retrieve the instance metadata. If the request is successful (status code 200), we parse the response content as JSON and print it in a nicely formatted JSON format using json.dumps().

Please note that this code should be executed within the Azure instance itself, as it relies on accessing the IMDS endpoint from within the instance.

Feel free to customize and integrate this code into your desired application or script as needed.