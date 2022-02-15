To run in docker just run: 

  docker run --name some-nginx -v ${PWD}:/usr/share/nginx/html:ro -d -p 8080:80 nginx
