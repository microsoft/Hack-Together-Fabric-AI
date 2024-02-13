# Access Azure OpenAI for Hack Together, for Free!

**We've made it quick and easy to get access to Azure OpenAI models for the duration of Hack Together!**

By using our Azure OpenAI Proxy service you'll get access to keys and endpoints that work just like the real ones you get from using the Azure Portal and Azure OpenAI Studio to deploy your own models. 

When you get access to Azure OpenAI yourself, all you need to do is switch over your endpoints and keys to get up and running on your own resources

## Get started
To gain access:

1. **Register for this event** at this URL: [https://aka.ms/Hacktogether-AI-register](https://aka.ms/Hacktogether-AI-register) 

2. **Login with GitHub** using the button in the top-right corner
![Screenshot of registration page with arrow pointing to top right corner.](images/proxy1.png  "Click login with GitHub")

3. Once logged in, you have access to the your API key for this event, click the copy icon. **Keep your key handy, for the following steps and for your hacking!**  
![Screenshot of proxy site page with arrow pointing to the copy button next to API Key.](images/proxy2.png "Click the copy button to copy your key")

4. **Go to the AI Proxy Playground** at this URL: [https://aka.ms/Hacktogether-AI-playground](https://aka.ms/Hacktogether-AI-playground)


5. **Enter your API key** in the text box in the top-right corner and click ***Authorize***
![Screenshot of proxy playground page with arrow pointing to API text entry field and authorize button.](images/proxy3.png "Enter your key and hit 'Authorize'")

6. **You should now see the event name** "Hack Together Fabric AI" in the top-right corner!
![Screenshot of proxy playground page with a tick and an arrow pointing to the event name "Hack Together Fabric AI" that appears once you have succesfully entered a key for the event.](images/proxy4.png "When you see the event name you have succesfully entered your key")

7. **You're ready to test your set up**, do this on this page by writing a message in the **Chat Session**. You should receive a message back in a few sedconds! *(You won't be able to test using the Image tab, because DALLE.2 is not enabled for this workshop.)*
![Screenshot of proxy playground page with an arrow pointing to the input field, where the message /Hello" has been writen.](images/proxy5.png "Test the service using the Chat feature by writing a message")

8. **Once you receive a message you know you are ready to hack!**
![Screenshot of proxy playground where the AI has responded with a message that says "Hello! How can I assist you today?".](images/proxy6.png "When you receive a response you are ready to hack!")

## Using the Endpoint 

**Endpoint**: https://polite-ground-030dc3103.4.azurestaticapps.net/api/v1

**Key:** Use the key you got in step 3 above.

For this event we have provided access to a few specific models. **You have up to 2000 requests per model per day.**

| Model  | Model Name  | Docs |   |   |
|---|---|---|---|---|
| GTP 3.5  |  gtp-35-turbo-16k |   |   |   |
| GTP4 |  gtp-4 |   |   |   |
| Embeddings |  text-embedding-ada-002 |   |   |   |
| DALL.E 4 |  text-embedding-ada-002 |   |   |   |

*The models we are using are all hosted in the Sweden Central region. You won't need that information for your hacking purposes.*
