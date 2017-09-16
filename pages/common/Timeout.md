# timeout

> You can use the timeout command from GNU coreutils (you may need to install it first, but it comes in most, if not all, Linux distributions):
 
`timeout [OPTION] DURATION COMMAND [ARG]...`

> For instance:

`timeout 5 ./test.sh`

> Will terminate the script after 5 seconds of execution. If you want to send a KILL signal (instead of TERM), use -kflag
