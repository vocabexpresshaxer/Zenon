# Zenon
![python](https://img.shields.io/badge/python-3.x-red.svg)
![discord](https://img.shields.io/badge/discord-userbot-blue.svg)

a discord userbot framework to interact with users instead of normal bots

# Example
``` python
import zenon

token = "your-token"

def on_message():
    while True:
        chatid = "409879939400335362"
        message = client.get_message(chatid)
        if message == "!test":
            client.send_message(chatid, "sei grassa!")
        
if __name__ == '__main__':
    client = zenon.Client(token)
    client.func_loop(on_message)
```
# how to get the token
1. open discordapp.com
2. log in or sign up
3. once you log in or sign up press ctrl + shift + i
this should appear at your right side:
![alt text](https://image.ibb.co/eiD7Oc/rught_scode.png)
4. then press this button:
![alt text](https://image.ibb.co/iViwGx/righthttt.png)
5. go to where it says local storage and then press the website link:
![alt text](https://image.ibb.co/gyBoUH/roghttt.png)
6. after you have done so scroll down and find where it says "token"
![alt text](https://image.ibb.co/daUE3c/raght.png)
7. copy and paste the token
8. go and enjoy zenon!
