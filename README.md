# docker_nodejs
This repository is for building a nodejs app using dockerfile and node_alpine image
Buid image by
  >docker image build -t nodejsimage .
  
  
Run container by
  > docker container run -d -p 80:3000 nodejsimage
