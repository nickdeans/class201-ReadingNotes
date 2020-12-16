# Sending Form Data 

**Client/Server architecture** - At its simplest form, a client (most likely web browser) sends a request to a server using the HTTP protocol. The server answers the request using the same protocol. 
- An HTML form is just a more convenient user-friendly way to configure an HTTP request to send data to a server.

## CLient Side: How to send the data
- The <form> element defines how the data will be sent over. Its value must be a working relative or absolute url. EX below:

```
<form action="https://example.com>
<form action="/somewhere_else">
```

- The method attribute defines how data is sent. 
- The HTML protocol makes several ways to perform a request: The most common ways an HTML forms data can be transmitted is by using the GET method and the POST method. 

**GET Method** - used by browser to ask the server to send back a given resource. If a from is sent using this method then the data sent to the server is appended to the URL.

**POST Method** - method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request. If a form is sent using this method, the data is appended to the body of the HTTP request.

- You can retrieve HTTP requests by using your developer toools and looking at the "network" tab. Your form data will be shown there,

## Server Side: retrieving the data
- Whichever HTTP method you choose, the server receives a string that will be parsed in order to get the data as a list of key/value pairs.
- PHP provides some global objects to access the data. 

### Attribution
https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data