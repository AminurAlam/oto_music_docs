# PLAYLIST RELATED QUESTIONS

## How do I backup or save playlists ?
 - Go to playlist tab
 - select the playlists you wanna save by long pressing on them
 - a top bar will apper
 - click on the options button on top right of the screen
 - select 'Save as files'
other method(this also works with the Favourites and History):
 - open the playlist you wanna save
 - click on the three dots on top right
 - select 'Save as file'

## Where are the saved playlists located?
You can find the .m3u files you backed up in this directory:
`Internal Storage/Playlists/Oto Music/playlist_name.m3u`

## How do I import the saved playlist ?
 - go to the playlist tab
 - click on the floating button with '+' symbol
 - select 'External playlist' to import from other apps
 - select 'Import playlist' to load playlists that you had saved

## How can I sort the songs in a playlist?
Sorting playlist isn't available for now

## What does the last added & recently played interval settings do?
The recently added section only shows the songs for a certain time period.
If you turn it to a week only those songs will appear which has been added in the time interval of a week.
Anything before that won't show up in the 'last added' list.

---

# TAGS RELATED QUESTIONS

## What are the meaning of the tags in oto ?
 - Title: This is the name of the song
 - Album: This is the name of the album
 - Artist: This is the name of the artist who performed the song
 - Album Artist: Name of the Artist/Band/Orchestra who made that album
 - Composer: The name of the person or group who wrote/composed the track
 - Genre: This is the type of music
 - Year: The year the audio file or song was created
 - Track Number: The track number that the audio file or song appeared on the album
 - Track Total: The total number of songs in the album
 - Disc Number: The number of the disc in a multi-disc album set that this track belongs to
 - Disc Total: The total number of the disc in a multi-disc album
more tag details: https://www.nch.com.au/kb/10061.html

## What is ReplayGain ?
Sometimes a track is pretty loud and the next one is really low and needs more volume.
Replay gain adjusts the volume and tries to make all tracks you play have the same basic subjective loudness.
This avoids the common problem of having to manually adjust volume levels between track.

## How do I use ReplyGain ?
You can use tag editors to change replay gain tags
this tag can be applied to either a track or the whole album

## What is ReplayGain preamp ?
Incase you are not satisfied by the replaygain value, you can set preamp which gets added or substracted to the replaygain value.
    original replaygain value = r
    preamp value = p
    new replaygain value = r+p

---

# LYRICS RELATED QUESTIONS

## How to download and use synced lyrics ?
There's an inbuilt button to download synced lyrics, which uses API to get lyrics.
If oto can't  find it u can manually download it from https://www.syair.info
You can  either copy/paste the text(aka embedding) or download .lrc files
(you'll need to make sure the song and lyrics have same file name)

## What is a .lrc file ?
The LRC file type is primarily a Lyric File. When an audio file is played on supported players, the song lyrics are displayed. The lyrics file generally has the same name as the audio file, with a different filename extension. For example, song .mp3 and song .lrc. Also If the file name is not the same as the music file name, you can rename it by keeping the extension the same. The LRC format is text-based and works the same way video subtitles work

## How can  I delay synced lyrics and match it with sound ?
Synced lyrics has it own tags like [ar: ] and [ti: ]
You can use the tag [offset: ] to sync the lyrics
example:-
[ar:Paramore]
[ti:Optimistic]
[al:RIOT!]
[offset:-100]
`+ shifts time up, - shifts time down`

---

# AUDIO AND FORMAT RELATED QUESTIONS

## Does oto support Flac/Hi-Res/24 bit audio?
Oto is just an app an, the thing responsible for audio playback is your android device
if your phone supports 24 bit hires audio then oto can play it
Same with audio format, if your device supports the format then Oto will be able to play it

## What audio formats does Oto support?
The supported audio formats depend on your phone, if it is able to play the format then oto will be able to play them too
Some commonly supported formats are mp3, flac and wav
and commonly unsupported formats are alac, wavpack

---

# TRANSLATION

## How can I help with translation?
you can ask the dev to get a link to the translation website
you can check what languages are available to be translated link
if the language you want to translate isn't here then ask the Dev to open it.

## How do I enable translation?
there's no in app option to change language
you'll have to go to phone's settings and change language

## There is an error in translation
you can ask the user who did the translation to fix it

---

# OTHER QUESTIONS

## Oto doesn't show the songs I've downloaded
 - Go to Settings and change 'Filter Song by Duration' to zero
 - Check if your music folder contains a '.nomedia' file. Delete it if you have it. It's a hidden file so make sure to enable hidden files/folders in your file manager
 - Try manually scanning the media folder or reboot to refresh the media store. The scan option is available in the folder tab.
 - If your audio files are stored on an SD card, try moving them to internal memory then back to SD card
 - At last clear 'media storage' app's data (not cache). To find this app, head to system settings / apps / enable system apps and clear data
 - How do I get the beta releases in Playstore ?
 - you can submit your email to Piyush so he can add it to beta. after being approved you'll see a "join beta" button in playstore
 - if you are not in beta don't worry, the apk will be uploaded here

## What is a  cue sheet ?
A cue file is a text file that defines the way tracks are organized on compact discs (CDs). It may contain the song name, performer, and length of each track on the disc. The cue file helps to identify where a track begins & ends, because a CD has the songs in one single file instead of being separated.
