Display Song Lyrics On Desktop In Ubuntu 14.04
================================================================================
![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/display_lyrics_desktop_Ubuntu.jpeg)

Apart from free streaming music, what I like the most in [Spotify][1] is its lyrics plugin. At times I don’t understand all of the words of the song, specially if it’s rap. [TuneWiki][2] plugin comes handy in this case. While TuneWiki has plugins for Windows Media Player and iTune, what options do we have on desktop Linux?

If you have been using desktop Linux for sometime, you might have heard of [OSD Lyrics][3]. It is a small application that **displays song lyrics on the desktop**. You can use it with several audio players such as Rythmbox, [Banshee][4], [Clementine][5] etc.

### Install OSD Lyrics in Ubuntu 14.04 and Linux Mint 17 ###

OSD Lyrics was actively maintained through its official PPA about 2 years back. There is no development anymore. While the PPA is no longer usable, the executables (.deb) can be downloaded from the website. Though these executables are originally for Ubuntu 12.04 Precise Pangolin, these files work very well in Ubuntu 14.04 also. Let’s see **how to install OSD Lyrics in Ubuntu 14.04 and Linux Mint 17**.

Go to the [download page of OSD Lyrics][6]. Get the .deb files depending upon [whether you are using 32 bit or 64 bit Ubuntu][7]. You will find the files on the top.

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/OSD_Lyrics_Download.jpeg)

Once downloaded, just double click on it to install it via Ubuntu Software Center. Alternatively, you can [use Gdebi to quickly install .deb packages][8].

### How to display lyrics in Ubuntu and Linux Mint using OSD Lyrics ###

Once installed, you can run OSD Lyrics from the Unity Dash:

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/Open_OSD_Lyrics_Ubuntu.jpeg)

On the first run, it will detect the existing players which are compatible with OSD Lyrics. You can set a default player which will be opened automatically each time you start OSD Lyrics.

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/OSD_Lyrics_Default_Player.jpeg)

One thing to note is that unlike [Shazam][9] etc, OSD Lyrics doesn’t find the lyrics from the audio, rather it uses the information linked to the music files such as name, album, artist etc. So make sure that you have music files from “respectable sources” or keep the file information correct and updated.

If it recognizes the music files, it will display the lyrics on the desktop in Karaoke format:

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/Dsiplay_Lyrics_Ubuntu.jpeg)

There are plenty of configuration options available with OSD Lyrics. You can change the font, size behavior of the lyrics display among many other things.

How do you like OSD Lyrics? Do you use some other Lyrics plugin? Do share your views with rest of us.

--------------------------------------------------------------------------------

via: http://itsfoss.com/display-song-lyrics-desktop-ubuntu-1404/

译者：[译者ID](https://github.com/译者ID) 校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创翻译，[Linux中国](http://linux.cn/) 荣誉推出

[1]:http://itsfoss.com/install-spotify-ubuntu-1404/
[2]:http://www.tunewiki.com/
[3]:https://code.google.com/p/osd-lyrics
[4]:http://banshee.fm/
[5]:https://www.clementine-player.org/
[6]:https://code.google.com/p/osd-lyrics/downloads/list
[7]:http://itsfoss.com/how-to-know-ubuntu-unity-version/
[8]:http://itsfoss.com/install-deb-files-easily-and-quickly-in-ubuntu-12-10-quick-tip/
[9]:http://www.shazam.com/