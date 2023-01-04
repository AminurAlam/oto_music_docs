# Oto Music Documentation


---


## PLAYLIST RELATED QUESTIONS


#### How do I backup or save playlists?
 - go to the playlist tab
 - select playlists by long pressing on them
 - a bar will appear on top
 - click on the three dots button on top right of the screen
 - select 'Save as files'

Other method (this also works with the Favourites and History):

 - open a playlist
 - click on the three dots on top right
 - select 'Save as file'


#### Where are the saved playlists located?
Backed up playlists can be found in this directory:

`Internal Storage/Playlists/Oto Music/playlist_name.m3u`


#### How do I import the saved playlist?
 - go to the playlist tab
 - click on the floating button with '+' symbol
 - select 'Import playlist' to load playlists saved in a m3u file
 - you can also select 'External playlist' to import from other apps


#### What does the last added & recently played interval settings do?
The recently added section only shows the songs for a certain time period.
By changing it to 'This Week', only songs added this week will appear.
Anything before that won't show up in the 'last added' list.


---


## TAGS RELATED QUESTIONS


#### What are the meaning of the tags in Oto?

| Tag           | Description     |
|-------------- | --------------- |
| Title         | This is the name of the song |
| Album         | This is the name of the album |
| Artist        | This is the name of the artist who performed the song |
| Album Artist  | Name of the Artist/Band/Orchestra who made that album |
| Composer      | The name of the person or group who wrote/composed the track |
| Genre         | This is the type of music |
| Year          | The year the audio file or song was created |
| Track Number  | The track number that the audio file or song appeared on the album |
| Track Total   | The total number of songs in the album |
| Disc Number   | The number of the disc in a multi-disc album set that this track belongs to |
| Disc Total    | The total number of the disc in a multi-disc album |

More details about tags available at [nch.com.au](https://www.nch.com.au/kb/10061.html)


#### What is ReplayGain?
Sometimes a track is pretty loud but the next one is really quiet.
Replay gain adjusts the volume and tries to make all tracks have the same basic subjective loudness.
This avoids the common problem of having to manually adjust volume levels between track.


#### How do I use ReplyGain?
Tag editors can be used to change replay gain value of songs.
Currently Oto doesn't support editing ReplayGain tag.


#### What is ReplayGain preamp?
In case you are not satisfied by the ReplayGain value, you can add preamp to it.

```
    o = original replaygain value
    p = preamp value
    new replaygain value = r + p
```


---


## LYRICS RELATED QUESTIONS


#### How to download and use synced lyrics?
There's an inbuilt button to download synced lyrics, which can search for lyrics.
Either copy/paste the text (embed) or download `lrc` files from [syair](https://www.syair.info).
Make sure the song and lyrics have same file name or it won't work.


#### What is a .lrc file?
The LRC file type is primarily a Lyric File.
When an audio file is played on supported players, the song lyrics are displayed.
The LRC format is text-based and works the same way video subtitles work.
The lyrics file generally has the same name as the audio file, with a different filename extension.

Example:
```py
'song name.flac' and 'song name.lrc'
```


#### How can I delay synced lyrics and match it with sound?
Synced lyrics has it own tags like [ar: ] or [ti: ].
You can use the tag [offset: ] to get the audio and lyrics in sync.

\+ shifts time up, \- shifts time down and time is in milliseconds

Example:
```
[ar:Arctic Monkeys]
[ti:Knee Socks]
[al:AM]
[offset:-100]
```


---


## AUDIO AND FORMAT RELATED QUESTIONS


#### Does Oto support Flac/Hi-Res/24 bit audio?
24 bit audio output depends on what kind of hardware you have.


#### What audio formats does Oto support?
The supported audio formats depend on the phone, if it can play the format then Oto will be able to play them too.

Some popular supported formats are mp3, flac, wav, ...
Usually unsupported formats are alac, wavpack, ...


---


## TRANSLATION


#### How can I help with translation?
Ask the dev to get a link to the translation website, and check what languages are present for translated.
If the language you want to translate isn't there, ask the Dev to add it.


#### How do I enable translation?
There's no in-app option to change language, go to phone's settings and change the language there.


#### What if there is an error in translation?
Ask the user who did the translation to fix it.


---


## OTHER QUESTIONS


#### Oto doesn't show the songs I've downloaded
 - go to Settings and change 'Filter Song by Duration' to zero
 - if the folder contains a file named '.nomedia' delete it
 - try manually scanning the media folder or reboot to refresh the media store
 - if the files are stored on a SD card, try moving them to internal storage then back to SD card
 - at last clear app data of 'media storage', to find this app head to `system settings > apps > show system apps` and clear data


#### How do I get the beta releases in Playstore?
You can give your email to Piyush so he can add it to the list of beta testers.
After being approved a 'join beta' button will appear in play store.
If you are not in beta, the apk will be uploaded in the discord server for everyone.


#### What is a cue sheet?
A cue file is a text file that defines the way tracks are organized on compact discs (CDs). It may contain the song name, performer, and length of each track on the disc. The cue file helps to identify where a track begins & ends, because a CD has the songs in one single file instead of being separated.
