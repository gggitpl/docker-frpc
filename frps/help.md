- `docker build -t frps .`
- `docker run --name frps -p 80:80 -p 443:443 -p 7500:7500 -p 6000:6000 -p 7000:7000 -d frps`