# WEB-SERVER
This project uses the framework `httplib` used as `httplib.h` & database `sqlite3`.

## How to run
 `g++ main.cpp  -l sqlite3`
```
If you haven't installed sqlite3 you should first install sqlite3.
```
Command to install `sqlite3` on `Debian` based systems:
```
sudo apt-get update && sudo apt-get install sqlite3 libsqlite3-dev
```
To get into sqlite3 command prompt,
```
sqlite3
```
 try performing `crud` there.

Don't try database with windows, it will fuck you up. Use `wsl` OR `linux through any other medium`

It's better if you if you go with `wsl` if you are in windows.

Further, if you are running the `backend service` in `wsl` and `front-end` service in windows, I might need to forward a port there. 

Tip: use `code .` as you use in windows for opening the vscode directly in wsl, no need to install locally in `wsl` and also install latest powershell.


Use this guide: [WSL-microsoft](https://learn.microsoft.com/en-us/windows/wsl/install)

Good Luck :)
