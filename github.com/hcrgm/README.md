# Gobang
A multiplayer Gobang game used WebSocket. Powered by Golang.

# [Have a try with your friends!](http://gobang.daoapp.io/)
# Screenshots
![Home](screenshots/1.png)
![Waiting](screenshots/2.png)
![Game](screenshots/3.png)
![Game over](screenshots/4.png)
# Getting Started
You can get the releases [here](https://github.com/hcrgm/Gobang-Go/releases)

If you want to build yourself:

1. Install Go First.
2. Clone this project, then, just execute `install.sh`. You will get a `gobang` executable binary file.

Then, run this program.

1. Rename `config_sample.json` to `config.json`, configure yourself by editing the `config.json` file.
2. Run `nohup ./gobang > golang.log 2>&1 &`
3. Visit http://127.0.0.1:port (port config in config.json, int).

# Docker
Build:`docker build -t gobang .`

Run:`docker run --name gobang --rm gobang`

Pass the configuration:`docker run --name gobang --rm  -e XXX=XXX -e XXX=XXX gobang

Environments: See [Dockerfile](Dockerfile)
# LICENSE
GPLv3
