# Amadeus
A Telegram Chatbot written in Python3, making use of OpenAI's GPT3 model (Da Vinci Engine). You can fork and deploy this repo on heroku.



# Steps to get your python chatbot working
- Fork this repository 
- Make your forked repository private in order to keep your openAI and Telegram Keys safe.
- Now edit the file 'amadeus.py' and replace the keys with the ones you had copied.
- Save the file
- Open <a href='https://dashboard.heroku.com'>heroku</a>, register or login into your account. If you don't know how to do it, you can <a href='https://youtu.be/uFWd9ivmuUI'>watch this video</a>.
- Create a new application
- Go to settings, add new buildpack i.e python as we have created the chatbot in python
- Now, under deploy tab, link your github account and deploy the repo you just forked.
- And now coming to overview tab, configure the dyno and turn it on.
- That's it, your chatbot is ready. Enjoy.


