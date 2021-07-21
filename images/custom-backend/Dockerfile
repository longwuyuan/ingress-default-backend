FROM nginx:stable-alpine

COPY https://github.com/longwuyuan/ingress-default-backend/blob/26f89515845f7d36b1eaaea5f920f2f804205184/images/custom-backend/default.conf /etc/nginx/conf.d/default.conf
COPY https://github.com/longwuyuan/ingress-default-backend/blob/26f89515845f7d36b1eaaea5f920f2f804205184/images/custom-backend/default.conf /etc/nginx/nginx.conf
COPY https://github.com/longwuyuan/ingress-default-backend/blob/26f89515845f7d36b1eaaea5f920f2f804205184/images/custom-backend/content/error.html /var/www/html/error.html

RUN chmod -R 777 /var/cache/nginx/
RUN chmod -R 777 /var/run/
RUN chmod -R 777 /etc/nginx/
