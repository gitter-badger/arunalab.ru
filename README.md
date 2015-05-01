# Arunalab.ru

[![Join the chat at https://gitter.im/arunalabru/arunalab.ru](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/arunalabru/arunalab.ru?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Hi there! Anybody home?

[![Join the chat at https://gitter.im/krogh7/arunalab.ru](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/krogh7/arunalab.ru?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Development

To get started:

```bash
sudo apt-get install -y git python3-pip tmux
sudo pip3 install virtualenv tmuxp
git clone https://github.com/roll/arunalab.ru.git
cd arunalab.ru
virtualenv venv
source venv/bin/activate
pip3 install -r requirements.txt
tmuxp load -y2 .
```

Now site is available at localhost:8000.

For more information about using tmux/tmuxp:

- http://www.openbsd.org/cgi-bin/man.cgi/OpenBSD-current/man1/tmux.1?query=tmux&sec=1
- http://tmuxp.readthedocs.org/en/latest/

## Staging

https://arunalabru.herokuapp.com/
