# This Is My i3 Configuration

It uses polybar, rofi and i3lock

### Setup
```
git clone https://github.com/kraeki/.i3 ~/.i3
```

### Polybar Version
I compiled polybar from source. Take a look at this wiki https://github.com/jaagr/polybar/wiki/Compiling.

```
polybar --version
polybar 3.0.5-84-gc348c3e

Features: +alsa +curl +i3 +mpd +network
```
The polybar configuration is ~/.i3/polybar.conf.

It uses unicode characters and other symbols from two different fonts. Make sure you install
`FontAwesome` and `Hack-Font`. Both are availabe as debian packages.

If you just want to add the polybar configuration follow these steps:
```
cd ~/.i3
Download polybar.conf to ~/.i3/polybar.conf
Download run_polybar.sh to ~/.i3/run_polybar.sh
```
Add the these lines to you i3 config (~/.i3/config)
```
exec_always --no-startup-id $HOME/.i3/bin/run_polybar.sh
Remove bar {..} configuration
```

### Installing Backgrounds
```
cd ~/.i3/backgrounds
wget https://laughingsquid.com/wp-content/uploads/2015/05/december1994_1920.jpg
wget https://i.imgur.com/MFzUwwB.jpg
wget http://www.simonstalenhag.se/bilderbig/by_crossing_2560.jpg
wget https://www.vegard.net/wp-content/uploads/2017/04/by_upload2_2560.jpg
wget https://i.imgur.com/L5pDsLl.jpg
wget http://buzzworthy.s3.amazonaws.com/wp-content/uploads/2015/10/jakub-rozalski-machine-over-muscles1a.jpg
wget https://pbs.twimg.com/media/C8JPPyqVwAAOdbP.jpg
wget https://hypb.imgix.net/image/2014/10/digital-paintings-by-jakub-rozalski-2.jpg
wget https://cdna.artstation.com/p/assets/images/images/003/032/824/large/jakub-rozalski-august-1914-01a.jpg
```
