# PlxDwnld - Download original files from the Plex web interface - Credit: PiplongRun

If you are using Plex, but you are not the owner of a server, the option to download a file is missing from the Plex web interface. This bookmarklet lets you download original files regardless if you are the server owner or not. It's like Direct Play, but with a save button.

This initial version of the bookmarklet has been tested in and works with recent versions of Firefox, Safari and Chrome. It does not work in Internet Explorer at the moment. Edge and Opera browsers have not been tested yet.

Due to recent Plex Server Updates, Different Buttons will work for different Plex Server Versions. You will have to try each until one works. The one on top should work for most servers but just in case, the other buttons are below.

## How to install

Drag this button to your bookmark


[💾 PlexDwnld-7](javascript:(function(){if (typeof plxDwnld == 'undefined') {var jsCode = document.createElement('script');jsCode.setAttribute('src', 'https://raw.githubusercontent.com/Solaflex/plex-scripts/main/piplongrun/plex-DL7.js?ts=%27 + Math.floor(Date.now()/1000));document.body.appendChild(jsCode);} else {plxDwnld.init();}})())

## How to use

Open the Plex web interface https://app.plex.tv and browse to the details page of a media item. The bookmarklet currently works for Movies and TV Shows.
Click the bookmark button to get the download.



https://sharedriches.com/plex-scripts/piplongrun/
