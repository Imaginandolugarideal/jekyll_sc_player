# SoundCloud Player Tag
> Easily import a SoundCloud player in your Jekyll powered site/blog

Usage:
```
{% sc_player URI %}
```
where `URI` points to a valid resource (track, playlist or user).

Example:
```
{% sc_player https://soundcloud.com/waek/daze-ft-girl-is-tough-new-york %}
```

Configuration is done in the `_config.yml`:
```yml
sc_player:
  auto_play: false # Whether to start playing the widget after it’s loaded
  buying: true # Show/hide buy buttons
  liking: true # Show/hide like buttons
  download: true # Show/hide download buttons
  sharing: true # Show/hide share buttons/dialogues
  show_artwork: true # Show/hide artwork
  show_comments: true # Show/hide comments
  show_playcount: true # Show/hide number of sound plays
  show_user: true # Show/hide the uploader name
  start_track: 0 # Preselects a track in the playlist, given a number between 0 and the length of the playlist.
```
See https://developers.soundcloud.com/docs/api/html5-widget#params for more informations on player's parameters.

# License
The MIT License (MIT)

Copyright (c) 2014 itsbrnrd

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
