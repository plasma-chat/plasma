# Plasma
## An IRC-Like chatting network

Plasma is a chatting system similar to IRC, matrix or discord.  
It is powered by [Python](https://python.org), [TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol), and [JSON](https://json.org).

---

##  Installation
### Manual Install

The following script should install plasma (depending on what you want):
```
python3 -m pip install iikp iipythonpy
python3 -m pip install colorama  # optional: windows only

# If you want both client+server:
git clone https://github.com/plasma-chat/plasma
cd plasma

# Client only
git clone https://github.com/plasma-chat/plasma-client
cd plasma-client

# Server only
git clone https://github.com/plasma-chat/plasma-server
cd plasma-server
```

For all clients, the entrypoint is `client.py`, servers use `server.py`.  
For specific launch options and configuration, check the following repos:
  - [Plasma Client Info](https://github.com/plasma-chat/plasma-client)
  - [Plasma Server Info](https://github.com/plasma-chat/plasma-server)

### Non-technical Install

This section is for people who don't know much about programming.  
Before you install Plasma, check that you have the following:
  - Python 3.8+ (3.9 or above is recommended | [Download Here](https://www.python.org/downloads/))
    - Ensure you check the `Add to PATH` option during installation.
    - Running Linux? You should already have an good enough Python install.
        - If you don't, install `python3` from your package manager.
  - Pip (should come with Python **if you added it to PATH**)

**Windows users:**
- Open a command prompt (cmd.exe)
- Run the following command: `pip install iikp iipythonpy colorama`
- Close the command prompt

**Linux users:**
- Launch your terminal emulator
- Run `python3 -m pip install iikp iipythonpy`
    - Pip not found? Run `wget https://bootstrap.pypa.io/get-pip.py && python3 get-pip.py`
        - After pip installs, you can `rm get-pip.py` then rerun the dep install.

- Exit your terminal emulator

Now that you have the dependencies, head to the top of this page.
- Select the green `Code` button
- Click the last option, `Download as ZIP`

You can now go to your downloads folder, right click, and extract.
- You can also delete `plasma.zip` after you extract it.

Now simply go into the `plasma/` directory that was extracted.

### Launching Plasma

If you're dealing with a server (and not a client), you should refer to [this README](https://github.com/plasma-chat/plasma-server).
Assuming you're in the `plasma` folder, you can double click `client.py` to launch it.

If you're in a terminal, run the following:
- Windows: `py client.py`
- Linux: `python3 client.py`

To configure your client or launch it differently, check [this](https://github.com/plasma-chat/plasma-client).

---
© 2021 [iiPython](https://github.com/ii-Python)
