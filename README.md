# Wordpress Docker and Windows WSL
If you are trying to run Wordpress within a docker environment on your Windows machine (with Windows for Linux Subsystem - WSL) - this may work for you.

- Create the directory on your Linux Ubuntu drive (accessed via Windows Explorer)
- Create a docker compose file copied from this repo (filename: **docker-compose.yml**)
- Open up a command line tool, eg the CLI tool inside Visual Studio
- Run **docker --version** to confirm you have Docker installed
- Run **docker-compose up -d**
- That should do ya!
