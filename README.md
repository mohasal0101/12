
# Readings: CRUD
Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.
## Reading

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

-   100’s = Informational status codes, these are used to inform the client that the request was received and understood.
-   200’s = Success codes, these are used to inform the client that the request was successfully received, understood, and accepted.
-   300’s = Redirection codes, these are used to inform the client that the resource they are requesting isn’t available at the expected location anymore.
-   400’s = Client error codes, these are used to inform the client that there was a problem with their request.
-   500’s = Server error codes, these are used to inform the client that there was a problem with the server. <br> <br>
1.  What is a status code 202?
This code tells the client that the request has been accepted for processing, but the processing has not been completed.
2.  What is a status code 308?
This code tells the client that the resource they are requesting has been moved permanently to a new location.
3.  What code would you use if an update didn’t return data to a client?
204 No Content
4.  What code would you use if a resource used to exist but no longer does?
410-Gone.
5.  What is the ‘Forbidden’ status code?
403-Forbidden

## Videos

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)  - First 20 minutes

1. So that we can hide our database string from the public.
2. Is a software that provides common services and capabilities to applications outside of what’s offered by the operating system.
3. It parses incoming requests with JSON payloads and is based on body-parser.
4. This is a parameter, it is used to capture the value of whatever we specify after the “/”.
5. PUT is used to update the whole resource, and PATCH is used to modify a specific resource.
6. By using the default property.

8. this code tells the client that the server encountered an unexpected condition that prevented it from fulfilling the request. <br> <br>
9. -   200 OK, this code tells the client that the request has succeeded.
    -   201 Created, this code tells the client that the request has succeeded and has led to the creation of a new resource.
