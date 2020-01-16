# 01_15_2020_DjangoREST_TUT

docker build -t some-content-nginx .

docker run --name some-nginx -d -p 8080:80 some-content-nginx

Then you can hit http://localhost:8080 or http://host-ip:8080 in your browser.