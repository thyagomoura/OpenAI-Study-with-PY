# Simple Chatbot with Py

#### obs: 
You must have python3 and pip on your machine
You need to have a key that you can get from the official [openai website](https://beta.openai.com/account/api-keys)

### Using:
Create a new Python shell session in your code edit and use as an example:

```py
>>>> from chatbot import ask, append_interaction_to_chat_log
>>> chat_log = None

>>> question = 'Who played Avengers in the movie?'
>>> answer = ask(question, chat_log)
>>> answer

>>> chat_log = append_interaction_to_chat_log(question, answer, chat_log)

>>> question = 'Was he in any other great roles?'
>>> answer = ask(question, chat_log)
>>> answer
```
