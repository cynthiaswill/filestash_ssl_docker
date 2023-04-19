#### this is the filestash app wrapped with https layer served by nginx

- cd into cert directory and run `bash mkcert.sh` to make a new certification and key

- cd back into repo root and run `docker-compose up -d`

- after running docker-compose, use
  ` sudo nano /etc/hosts`
  to add `127.0.0.1 my-filestash.local` at the bottom of the list
