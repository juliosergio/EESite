#!/bin/bash 
USER=checo
HOST=172.16.19.27
DIR=EESite/
rsync -avz --exclude-from 'exclude-list.txt' --delete public/ ${USER}@${HOST}:~/${DIR}
exit 0
