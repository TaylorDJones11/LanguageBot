# Language Translation Bot with Amazon Lex 🤖
- [Blog Post](https://dev.to/onetayjones/aws-lex-building-a-language-translation-bot-4plm)

## Overview
This project is a language translation bot built using Amazon Lex. The bot enables users to translate words or sentences into different languages by simply typing the text into the chatbot. It then returns the translated output, making cross-language communication seamless and easy.

<img width="681" alt="Screenshot 2024-11-14 at 12 54 45" src="https://github.com/user-attachments/assets/f5ea641c-6cf8-4721-a453-afa3277c43fe">


## Steps to Build the Bot 👩🏽‍💻

1. **Create an Empty Chatbot**  
   Begin by creating a new bot in Amazon Lex with a basic configuration.

2. **Specify Intents and Slots**  
   - Define user intents, like `TranslateIntent`, to manage translation requests.
   - Add slots to capture details, such as the target language.

3. **Specify Fulfillment**  
   Set up fulfillment to manage how Lex responds, using AWS Lambda to handle the request and Amazon Translate for translation.

4. **Create an IAM Role**  
   Set up an IAM role with permissions for Amazon Lex, Lambda, and Translate to enable secure service access.

5. **Create a Lambda Function**  
   Develop a Lambda function to process the translation request by interacting with the Amazon Translate API.

6. **Test the Lambda Function**  
   Verify the Lambda function works as expected by running test cases with sample phrases.

7. **Test the Chatbot**  
   Integrate and test the bot in the Amazon Lex console, checking for correct translations.

## AWS Services Used 🛠

- **Amazon Lex**: To build and manage the chatbot and define the conversation flow.
- **AWS Lambda**: To handle the translation requests using Amazon Translate.
- **AWS IAM**: To manage roles and permissions for secure service access.
- **Amazon Translate**: To translate text based on the specified target language.

## Conclusion
This language translation bot project demonstrates the powerful integration capabilities of Amazon Lex with AWS services. It’s an exciting way to learn about serverless applications, natural language processing, and multilingual communication with AWS. Happy building!

![Chatbot](https://github.com/user-attachments/assets/b608551b-91ae-46fb-821e-7fd9f4d9a744)

