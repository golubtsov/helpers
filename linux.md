### добавить в автозагрузку
```
sudo systemctl enable имя_службы
```

### удалить в автозагрузку
```
sudo systemctl disable имя_службы
```

### посмотреть порты
```
ss -tulpn
```

```
docker volume ls
```

```
docker volume rm my-vol
```

```
docker rmi my_image
```

### Если не работает контейнер mysql из-за процесса
https://stackoverflow.com/questions/36103721/docker-db-container-running-another-process-with-pid-id-is-using-unix-socket\
