# cowrie-output-telegram
Telegram plugin for cowrie HoneyPot

This is an output plugin to be used with cowrie honeypot
https://github.com/cowrie/cowrie

The telegram.py file should be copied to src/cowrie/output/ (inside cowrie directory)


Add config above to etc/cowrie.cfg

[output_telegram]
enabled = true
bot_id = 979821124:AAEfMZSWY0Bbt0nqGwfe5994XkPRWt6JZAo
chat_id= 814725654


Message sent to Telegram can be customized based in this fileds
https://www.misp-project.org/objects.html#_cowrie


