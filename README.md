# mpv-remote-app

Refer to [mcastorina/mpv-remote-app](https://github.com/mcastorina/mpv-remote-app) for info about the original project. 

I'm mostly interested in the included python scripts, less in the app, but I'm hoping to keep the protocol mostly functional. 

### Prerequisite (Server)
Have server/server.py running, with a password as parameter

### Control
To get a control command line locally, run test/mpv-command. This has some extra features (some of which I didn"t get to work), but the send command will definitely work, accepting [plain, old mpv commands](https://mpv.io/manual/master/#list-of-input-commands). This script communicates with mpv through its unix socket (by default /tmp/mpvsocket). 
