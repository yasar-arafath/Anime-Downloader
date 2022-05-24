# Anime Downloader by Yasar Arafat
A Python script run in a docker container that uses Selenium and Headless Chrome to allow you to download anime from gogoanime.so easily.


### Step 1
Build the docker container.

```bash
docker build -t anime-py .
```

### Step 2
Run the `docker run` command specified below. 

#### WINDOWS
```bash
docker run --interactive --tty -v "$("C:/Users/user/Desktop/Air Video/!anime/"):/home" anime-py
```

