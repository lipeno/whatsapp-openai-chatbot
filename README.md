# Configuration
Before you begin, you will need to set up your OpenAI API key in the .env file. Here's how to do it:

1. Open the .env file in a text editor.
2. To get an API key for the OpenAI API, sign up for a free OpenAI account on the OpenAI website (https://openai.com/). You will need to provide your name, email address, and create a password.
3. Insert the following environment variable, which will hold the API key from your OpenAI account:
$ OPENAI_API_KEY="INSERT YOUR OPENAI API KEY HERE"

Once you have completed these steps, you will be able to use the OpenAI API key in your project to access the OpenAI API.

# Running the program
To start the program, enter the following command in the command line:
$ node index.js

If the command is successful, you should see the QR code displayed on the command line.
You can use this QR code to authenticate the Chatbot through the WhatsApp mobile app. After scanning the QR code, you should see a message indicating that the Chatbot is running and listening for messages.
To send a message to the Chatbot, use the # sign followed by your question in the WhatsApp chat. The Chatbot, powered by OpenAI, will automatically respond to your message with a generated response.