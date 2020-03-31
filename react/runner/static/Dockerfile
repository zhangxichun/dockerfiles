FROM nginx:alpine
ADD nginx_default.conf /etc/nginx/conf.d/default.conf
ADD ./dist /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]