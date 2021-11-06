## Apple Stock notification

This is my fork from [cisasntyi](https://github.com/SealinGp/cisasntyi): check iphone stock and send notification to your iphone

install **Bark - Customed Notifications** app, then add endpoint to yml file

### run local

```bash
bash dev.sh
```

### run in your private server

```bash
#build it
bash build.sh

#upload to your server
scp ./cisasntyi.tar.gz user@yourPrivateServerIp:/home

#run in your server
ssh -t user@ip cd /home
tar -xvzf cisasntyi.tar.gz && cd cisasntyi && bash start.sh
```
