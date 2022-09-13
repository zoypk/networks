https://drive.google.com/drive/folders/1YiAqXgsaJIE8XVUZJv7JiBsGRUfbb_rm

gcc -o udpserver udps.c
./udpserver 2000

gcc -o udpclient udpc.c
./udpclient 127.0.0.1 2000

gcc -o ipthread
