# Post-Button

The Post button lets people post songs to their stream while adding a message. By including the [Undrtone](www.undrtone.com) script and applying specific class and attribute values buttons can be created to open the Undrtone Post dialog. This is made easy with the flexible format of the query parameter, able to match URLs and service keys. Buttons are always square by default at 20px, the size can be increased up a to maximum size of 50.

### Script Embed

Include this short JavaScript snippet at the end of your page, before the closing body tag, to apply the post functionality.

```
<script type="text/javascript">
!function(a,b){var c,d=a.createElement(b);d.type="text/javascript",d.async=1,d.src=a.location.protocol+"//cdn.undrtone.com/build/buttonpost.min.js",c=a.getElementsByTagName(b)[0],c.parentNode.insertBefore(d,c)}(document,"script");
</script>
```

## HTML Element Attributes

To create a button with default size to post the song Dogs by Pink Floyd follow the format below.

```
<div class="undrtn--post" data-song="spotify:track:1kAvmwfFoSwfyfuW5RmfD0">Pigs - Pink Floyd</div>
```

To create a button at 50px to post the song Ancient Light by Allman Brown follow the format below.

```
<div class="undrtn--post" data-size="50" data-song=""http://soundcloud.com/allmanbrown/ancient-light1">Pigs - Pink Floyd</div>
```

| Attribute | Description
|-----------|------------
|class      | Any element with class "undrtn--post" will be have a click event added
|data-song  | URL or service key of the song to post see above for accepted formats
|data-size  | (optional) by default the size will be 20px square. The minimum is 20px, maximum 50px

## Accepted URLs and service keys

Use any of the below formats in the data-song attribute to post a song.

### Soundcloud

https://api.soundcloud.com/tracks/164639676
https://soundcloud.com/preign/dnf-p-reign-ft-drake-future

### Rdio
* t50024190
* http://rd.io/x/QitApA2h/
* http://www.rdio.com/artist/The_Drones/album/Wait_Long_By_the_River_and_the_Bodies_of_Your_Enemies_Will_Float_By_1/track/Another_Rousing_Chorus_You_Idiots!!!/

### Spotify
* 6rqhFgbbKwnb9MLmUQDhG6
* spotify:track:6rqhFgbbKwnb9MLmUQDhG6
* http://open.spotify.com/track/6rqhFgbbKwnb9MLmUQDhG6

### Beats Music
* tr694433
* https://listen.beatsmusic.com/albums/al694421/tracks/tr694433
* beatsmusic://beatsmusic.com/albums/al6910269/tracks/tr6910289

### Deezer
* http://api.deezer.com/track/3135556
* http://www.deezer.com/track/3299289

## Need Help?

Contact us at support@undrtone.com

