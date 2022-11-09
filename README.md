# TBD_6.2
npm init 
npm i node
npm i express
npm i request
docker image build -t acme/catalog:1.0 .
docker run --rm -it --name catalog -p 3000:3000 acme/catalog:1.0