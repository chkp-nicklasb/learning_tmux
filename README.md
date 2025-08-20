# learning_tmux

### To create a new tmux session called test:
```
tmux new -s <session-name>
```
### To detatch from current session:
```
CTRL-b + d
```
### To list available sessions:
```
tmux ls
```
### To attatch to specific session: 
```
tmux a -t <session-name>
```
### To attach to a remote server on port 2222
```
ssh -l <username> <servername> -p 2222 -t tmux attach-session

```
### To attach to a remote server of port 2222 to a specific session:
```
ssh -l <username> <servername> -p 2222 -t tmux a -t <session name>
```
