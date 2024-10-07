<div align='center'>
    <img style='border-radius: 10px' src='https://iili.io/dpWWXp9.jpg' alt='yasha image' >
    <br>
    <br>
    <b>Fast & powerfull Rubika API library</b>
    <br>
    <a href='https://github.com/abli789/yasha'>GitHub</a>
    •
    <a href='https://rubika.ir/yasha_documents'>Documents</a>
</div>


# yasha 2.6.0
[![Downloads](https://static.pepy.tech/badge/yasha)](https://pepy.tech/project/yasha)
> Fast and powerfull Rubika API library for building self bots.


<hr>

### Install or Update:

``` bash
pip install -U yasha
```

<hr>

### Quick start:

``` python
from yasha import Client
from yasha.types import Message


client = Client("mySelf")

@client.on_message(regexp="hello")
def send_hello(message: Message):
    message.reply("**hello** __from__ ##yasha##")

client.run()
```

also you can enter your session data manually:
```python
from yasha import Client
from yasha.types import Message


auth_key = "abcdefghijklnopkrstuvwxyzazxcqwe"
private_key = "-----BEGIN RSA PRIVATE KEY-----\n..."

client = Client(auth=auth_key, private=private_key)

@client.on_message(regexp="hello")
def send_hello(message: Message):
    message.reply("**hello** __from__ ##yasha##")

client.run()
```

<hr>

### Features:
    
- **Fast** : *The requests are very fast and optimize.*

- **Powerful** : *While the library is simple, it has high speed and features that make your work easier and faster*

- **Easy** : *All methods and features are designed as easy and optimal as possible*


<hr>

### Social Media:
### <a href='https://rubika.ir/Yashar_ghost '>Rubika</a>

<hr>

### 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=abli789/yasha&type=Date)](https://star-history.com/#abli789/yasha&Date)