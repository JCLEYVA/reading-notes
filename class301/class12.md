## CRUD

1. HTTP status codes are used to indicate the response status of an HTTP request. Here are what each group of status codes generally represents:

100's = Informational responses indicating that the request was received and understood by the server, and to continue with the request or wait for further instructions.

200's = Success responses indicating that the request was successfully received, understood, and accepted by the server. These codes are often used to indicate the successful completion of a request.

300's = Redirection responses indicating that the requested resource has been moved or is located elsewhere, and that you should try a different URL or resource.

400's = user error responses indicating that the server was unable to fulfill the request due to an error or issue with the user's request. These codes are often used to indicate problems with the user input or request.

500's = Server error responses indicating that the server was unable to fulfill the request due to an error or issue with the server. These codes are often used to indicate problems with the server's functionality or configuration.

2. Status code 202 is an HTTP response status code indicating that the request has been accepted for processing, but the processing has not yet been completed. The response may include an estimate of when the processing will be completed.

3. Status code 308 is an HTTP response status code indicating that the resource has permanently moved to a new URL, and that the user should update its bookmarks or links to the new URL.

4. If an update didn't return data to a user, the appropriate status code to use would be 204 No Content. This indicates that the request was successful, but there is no response body to return to the user.

5. If a resource used to exist but no longer does, the appropriate status code to use would be 410 Gone. This indicates that the requested resource is no longer available and will not be available again in the future.

6. The 'Forbidden' status code is 403 Forbidden. This indicates that the server understood the request, but the server is refusing to fulfill it. This status is similar to 401 Unauthorized, but indicates that the client does not have access rights to the content.




## Things I would like to know more about