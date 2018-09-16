# DiscordBots
const Discord = require('discord.js')
const bot = new Discord.Client();
bot.login('NDkwNzIyNTk3ODY5NDUzMzEz.DoBcEg.kB8Z2Zs-AyDvbmmbLizGtUTuNnA');
//to turn off bot do Ctrl+c//
//to turn on bot do node . in terminal//
bot.on('message' , function(message){

    if(message.content == '$hello')
    {
        message.reply('i love you to!');
    }


});  


