# AI-Chatbot-with-NLP

*Company* : CODETECH IT SOLUTIONS

*Name* : PRAGYA SANTRA

*Intern ID* : CT08NGE

*Domain* : Python

*Duration* : 4 Weeks

*Mentor* : NEELA SANTOSH

## Description

The task involves developing a simple AI chatbot using the **Natural Language Toolkit (NLTK)** library, which facilitates the creation of conversational agents by utilizing various text-processing and language modeling techniques. The purpose of the chatbot is to respond to user inputs with predefined answers based on matching patterns. This process is known as **pattern-based matching**, where specific regular expressions (patterns) are defined to identify keywords or phrases in the user’s input, and corresponding responses are provided. The chatbot's functionality is limited to predefined responses, and it offers a simple, interactive interface where users can type messages and receive automated replies.

To start, the Python **NLTK** library is utilized. NLTK is a comprehensive platform used for building programs that work with human language data (text). It provides easy-to-use interfaces for over 50 corpora and lexical resources such as WordNet, as well as a suite of text-processing libraries for classification, tokenization, stemming, tagging, parsing, and more. The library also comes equipped with a module called `nltk.chat.util`, which is specifically designed for creating chatbots through pattern matching. The chatbot is initialized using a **Chat** class, which takes a list of regular expression patterns and responses.

The core of the chatbot lies in its **patterns and responses**. These patterns are regular expressions that match specific phrases or keywords in the user's input. For instance, the chatbot recognizes greetings such as "hi," "hello," or "hey" and responds with a set of friendly greetings like "Hello!" or "Hi there!". The responses are randomized, meaning that for each pattern, the chatbot will select a response randomly from the list of possible answers, providing a more natural interaction. The chatbot is capable of recognizing simple questions such as "What is your name?" or "How are you?", and it will provide an appropriate response based on the predefined patterns.

In addition to these simple interactions, the chatbot also includes a generic response for unrecognized input. When the chatbot encounters something that doesn’t match any of its patterns, it responds with a default message such as "Sorry, I didn’t understand that. Can you please ask something else?" This feature ensures that the chatbot can handle unforeseen input gracefully, even if it cannot provide a meaningful response.

The chatbot is further enhanced by the inclusion of **reflections**, which is a built-in dictionary in NLTK that allows the bot to replace pronouns and verbs in a way that makes the conversation feel more natural. For example, if a user says "I am doing well," the chatbot may reflect this by responding "You are doing well." This helps make the conversation flow more smoothly and appears less robotic. The `reflections` dictionary helps the chatbot transform the user’s input into a more meaningful and context-aware output.

The program starts by calling the `start_chat()` function, which opens an interactive conversation with the user. The user types a message, and the chatbot looks for a matching pattern. If the user types "quit," the program exits the loop, and the conversation ends. Otherwise, the chatbot responds based on the matched pattern. This loop continues, allowing the user to interact with the chatbot until they decide to exit by typing "quit".

This task demonstrates a basic yet effective method of creating a chatbot that relies on pattern matching. While this approach is simple and does not include advanced machine learning or deep learning techniques, it provides a functional conversational agent that can be expanded upon. More complex chatbots can be built by integrating additional NLP techniques, such as named entity recognition, part-of-speech tagging, and machine learning models for intent classification and response generation.


### Screenshot of the output


![Image](https://github.com/user-attachments/assets/caddffe8-c6cb-4f44-a4ed-12766e804ed0)

![Image](https://github.com/user-attachments/assets/7c328fde-fec1-42fa-ab2a-989c073d556a)
