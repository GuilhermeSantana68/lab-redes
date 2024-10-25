docker build -t guilherme68 .

docker run -d guilherme68

docker run -d 60296:80 guilherme68

wget localhost:60296

cat index.html

docker stop guilherme68

