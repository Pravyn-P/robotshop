FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -f /etc/nginx/nginx.conf
RUN rm -f /etc/nginx/dconf.d/deafualt.conf
COPY default.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
ENV CATALOGUE_HOST="catalogue"
