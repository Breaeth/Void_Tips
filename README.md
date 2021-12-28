# Void_Tips

### Enable wpa_supplicant by default 
```
sudo ln -s /etc/sv/wpa_supplicant /var/service
```
### Install Discord 
```
wget  https://dl.discordapp.net/apps/linux/0.0.16/discord-0.0.16.tar.gz | tar -xf
cd Discord ; sudo chmod +x Discord ; ./Discord
```

### Install Spotify or how to not install spotify 

```
sudo xbps-install spotifyd spotify-qt 
```
For spotify-qt just launch it in a terminal everything is clear like wather.

For spotifyd there is the wiki -> https://spotifyd.github.io/spotifyd/

And a useful video : https://www.youtube.com/watch?v=TaPWqXFtce8

And the brainless mode for launch it : 
```
spotifyd --no-daemon -u your_username -p your_password 
```
Tips : see the spotify.sh in this repo 

