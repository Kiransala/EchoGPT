# EchoGPT

This is a simple chat application that uses the OpenAI API to generate responses to user inputs. The front-end of the application is built using HTML, CSS, and JavaScript, and the back-end is built using Node.js and the Express framework.

## **Getting started**

To get started with this project, you will need to sign up for the OpenAI API and obtain an API key. Once you have your API key, create a **`.env`** file in the root directory of the project and add the following line to it:

```jsx
javascriptCopy code
OPENAI_API_KEY=<your API key here>
```

Next, you will need to install the project dependencies. To do this, run the following command:

```
Copy code
npm install
```

Finally, start the application by running the following command:

```
sqlCopy code
npm start
```

This will start the server on **[http://localhost:5000](http://localhost:5000/)** and launch the chat application in your default browser.

## **How it works**

The front-end of the application is built using HTML, CSS, and JavaScript, and it allows the user to enter a message and receive a response from the OpenAI API.

The back-end of the application is built using Node.js and the Express framework. When the user sends a message, the server sends a request to the OpenAI API, which generates a response based on the user's input. The response is then returned to the server, which sends it back to the client.
