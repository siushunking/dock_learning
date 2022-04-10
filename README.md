# dock_learning


```
FROM node 

WORKDIR /app

COPY  . /app

RUN npm install

EXPOSE 80 

CMD ['node', 'server.js']

```

# cmd 
1. docker build .  (.代表cmd 位於檔案路徑)
2. docker run (dock_id)
3. docker stop image_docker_name
4. docker ps (查看所有processor)
5. docker ps -a
6. docker run -p 3000:80 docker_id. 

如果有code有改變

