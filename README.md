# Indroduction
Our API has predictable, resource-oriented URLs and uses HTTP response codes to indicate API errors. We use built-in HTTP features, such as HTTP authentication and HTTP terminology, which can be understood by HTTP clients. JSON will be returned in all responses from the API, including errors.

# Responses
The API uses HTTP response codes to show success or failure of an API request. In general, 2xx codes indicate success, 4xx codes indicate an error that resulted from the provided information (e.g. a required parameter is missing or invalid, etc.), and codes in the 5xx range indicate an error connected with our servers.
