# Torrent-To-Google-Drive-Downloader
This Repo is a google collab codes which can be used to download torrent files directly to google drive. Can be used in networks which ban use of torrenting.
# How to use

- Click the (https://colab.research.google.com/github/unnideeraj/Torrent-To-Google-Drive-Downloader/blob/main/Torrent_to_GDRIVE.ipynb) link to open Collab.
- (>)Click run on first cell "Mount the Gdrive".
- (>)Install Lib Torrent.
- Replace the ```link = "PASTE YOUR MAGNET LINK HERE"``` with your Torrent magnet link.
- (>)Click Run and wait for the download to complete.
- Check the Gdrive folder for the files.
- Modify the ``` 'save_path': '/content/drive/My Drive/Torrent/' ``` for custom path or leave it as it is.
- ###Enjoy ToRrEnTing In Banned Networks###
- Use this``` # @title Install libtorrent [torrent library]```
```!python -m pip install --upgrade pip setuptools wheel```
```!python -m pip install lbry-libtorrent```
```!apt install python3-libtorrent```
