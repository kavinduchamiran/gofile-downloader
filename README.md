# GoFile Downloader


### Setup
First of all, clone this repository :

```bash
~$ git clone https://github.com/quatrecentquatre-404/gofile-downloader
```

Second, oh wait... There is not a second part, because it does not require any extra module.

### Config
Open up the ``config.json`` file and fill out fields.

``API_KEY`` : It's required to get the resources URL. You can find it when you're loading the GoFile page, using the dev tool, filtering by XHR, and observing the request. You will find this route : ``https://api.gofile.io/getAccountDetails?token=THE_API_TOKEN_HERE``.

``URL`` : It's the URL of the page you wish to download.

Now, you can figure out by yourself what to put in these quotes to download all the leaks you want.

### Run it !
Once you've updated all the config, you can run the script :
```bash
python3 tests.py
```
And there you go !

### Thanks !
I hope you enjoy my work. If you do, please, ⭐ this repository. If you have anything to report or to update, you can open an issue or a pull request, I'll give a look for sure.
