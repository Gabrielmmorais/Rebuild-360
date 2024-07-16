#puxando a imagem mais recente do nginx
FROM nginx

#Copiando o arquivo de configuração personalizada do nginx
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]