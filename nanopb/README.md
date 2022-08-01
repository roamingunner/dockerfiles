# nanopb image usage

## build 

docker build -t nanopb:latest .

## usage

docker run -it --rm -v `pwd`:/workspace nanopb:latest nanopb-generator   xxx.proto

