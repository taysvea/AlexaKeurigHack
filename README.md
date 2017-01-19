# AlexaKeurigHack

Control your Keurig through your Amazon Echo, using the Alexa Skills Kit and AWS IOT service.
You'll create an Alexa Skills Kit (ASK) app that fires off requests to AWS Lambda. 
You will register a Rasberry Pi as a device in AWS IoT. 
The Alexa app will call a function in Lambda, which will send a request to the Pi to activate a servo, which pushes down the brew button and starts your brew.

Create an Alexa Skills Kit (ASK) app, using the intent schema and sample utterances in this repo. 
Choose an invocation name like my Keurig.
Use the code in main.py as your Lambda function that the ASK skill will call. 
Substitute amzn1.echo-sdk-ams.app.<your-alexa-skills-id> with the ID of the ASK skill you created. When you create the function, set the "Event Source" to the Alexa Skills Kit.
Modify your ASK skill with the ARN of your newly created Lambda function.



