FROM nginx
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/nginx.conf
COPY default.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
ENV CATALOGUE_HOST=catalogue \
    USER_HOST=user \
    CART_HOST=cart \
    SHIPPING_HOST=shipping \
    PAYMENT_HOST=payment \