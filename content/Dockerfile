FROM busybox:1.36

WORKDIR /home

COPY style.css .
COPY index.html .
COPY ai-generated-8270263.jpg .

EXPOSE 3000

CMD ["busybox", "httpd", "-f", "-v", "-p", "3000"]
