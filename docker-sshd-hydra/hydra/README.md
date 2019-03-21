docker build -t nmap .

docker run -it --name namp  nmap:latest

docker run -it  --name namp nmap:latest --help

docker run -it  --name namp nmap:latest -v -A scanme.nmap.org

