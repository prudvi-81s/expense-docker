FROM nginx 
COPY code /user/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /ect/nginx/nginx.conf
# COPY expense.conf /ect/nginx/conf.d/expense.conf