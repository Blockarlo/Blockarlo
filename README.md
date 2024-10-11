- 👋 Hi, I’m @Blockarlo
- 👀 I’m interested in web 3 bot development 
- 🌱 I’m currently learning programming and violin
- 💞️ I’m looking to collaborate on crypto projects
- 📫 How to reach me https://t.me/Arlo_on_block on telegram
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Blockarlo/Blockarlo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
api_id =  '7511194140'

bot_token = '7511194140:AAFgW33r2JhhxtI4zaQWoIqne31nrb955gc'     
  
client = TelegramClient('bot', api_id=5434266369, .start(bot_token=bot_token) 

    @client.on(events.NewMessage)
async def handler(event):
    message = event.message.message
    await event.respond(f"Cloned response: {message}")

client.run_until_disconnected()             
