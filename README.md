#### obs: 
You must have python3 and pip on your machine
You need to have a key that you can get from the official [openai website](https://beta.openai.com/account/api-keys)


# 1 - Simple Chatbot

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
# 2 - Recipe Generator

### Using:
Create a new Python shell session in your code edit and use as an example:

```py
>>>> from ingredients import GPT_Completion
>>>> recipe = 'Provide a cooking recipe based on the following ingredients: \
\n \nApple \
\n \nWater \
\n \nChicken \
\n \nOlive oil'

>>>> GPT_Completion(recipe)
```
