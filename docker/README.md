# development

## build with

    docker build -t discourse:latest .
    
## run with
    
    docker run -p 3001:80 discourse:latest
    
## debug / login with
    
    docker exec -i -t <CID> /bin/bash