To connect to mysql, open mysql docker container in terminal

```
source ~/.bash_profile
sail exec -it mysql bash
```

Run the following command:

```
mysql --host mysql -u sail -p laravel
```

The password to it is available in `.env` file. 