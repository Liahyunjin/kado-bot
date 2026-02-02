# Kado Bot
## Running on your own server
### Prerequisites
- Docker
- Docker Compose
- Discord Bot Token (https://discordapp.com/developers/applications/)
- Mongo Database (https://mongodb.com/cloud/atlas)
### Running
1. Clone this repo
```
git clone https://github.com/LightYagami200/Kado-bot.git
```
2. Cd into the cloned repo folder
```
cd Kado-bot
```
3. Create a new file `.env` and add following:
```
MONGO_CONNECTION_STRING=<INSERT MONGO CONNECTION STRING HERE>
DISCORD_BOT_TOKEN=<INSERT DISCORD BOT TOKEN HERE>
```
4. Now run:
```
docker-compose start
```
![CodeRabbit Pull Request Reviews](https://img.shields.io/coderabbit/prs/github/Liahyunjin/kado-bot?utm_source=oss&utm_medium=github&utm_campaign=Liahyunjin%2Fkado-bot&labelColor=171717&color=FF570A&link=https%3A%2F%2Fcoderabbit.ai&label=CodeRabbit+Reviews)

