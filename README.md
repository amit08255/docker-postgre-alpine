### To build docker image use command -

```sh
sudo docker build -t postresql:12.5 .
```


### To run the image created use command -

```sh
sudo docker run -p 5432:5432 --name prostgres -e POSTGRES_PASSWORD=RaNd0MpA55W0Rd  postresql:12.5
```

It will create a new db called "postgres", with user "postgres" and set root password of "RaNd0MpA55W0Rd".