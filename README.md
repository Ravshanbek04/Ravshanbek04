/start ## Hi there 👋
   from telegram import Update
   from telegram.ext import Updater, CommandHandler, CallbackContext

   TOKEN = '@asuscombot'

   def start(update: Update, context: CallbackContext) -> None:
       update.message.reply_text('Salom! Botga xush kelibsiz!')

   updater = Updater(7899241002:AAF6tl2TJwqUxOO70SFo-hVw7rcS4EtiP5w)
   updater.dispatcher.add_handler(CommandHandler('start', start))

   updater.start_polling()
   updater.idle()
   
<!--
**Ravshanbek04/Ravshanbek04** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
