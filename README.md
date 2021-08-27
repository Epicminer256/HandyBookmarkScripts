# HandyBookmarkScripts
### Here are 17 bookmark scripts you can use on Chrome/ChromeOS. Some of these include Tab Hiders, Inspect Element (even if it is blocked), Soft/Hard reset, SoundBoard without going to any website, WiFi login portal detection, and others

# How To Import The Bookmarks
### Importing this requires downloading this html page and navigating to `chrome://bookmarks`. On the three dots to the top right hit import and select the html file. Move the "Tools" folder to the root of your bookmarks.

# Here are some examples of some in raw text

### Quick Tab Hider "makes it look like a google tab"
##### `javascript:var title = "Google";document.title = title;var fav = "https://freesvg.org/img/1534129544.png";function setFavicons(favImg){let headTitle = document.querySelector('head');let setFavicon = document.createElement('link');setFavicon.setAttribute('rel','shortcut icon');setFavicon.setAttribute('href',favImg);headTitle.appendChild(setFavicon);}setFavicons(fav);`

### Manual Tab Hider
##### `javascript:var title = prompt("Title?", "Home | Schoology");document.title = title;var fav = prompt("Icon URL?", "https://asset-cdn.schoology.com/sites/all/themes/schoology_theme/favicon.ico");function setFavicons(favImg){let headTitle = document.querySelector('head');let setFavicon = document.createElement('link');setFavicon.setAttribute('rel','shortcut icon');setFavicon.setAttribute('href',favImg);headTitle.appendChild(setFavicon);}setFavicons(fav);`

### Inspect Element
##### `javascript:var title = prompt("Title?", "Home | Schoology");document.title = title;var fav = prompt("Icon URL?", "https://asset-cdn.schoology.com/sites/all/themes/schoology_theme/favicon.ico");function setFavicons(favImg){let headTitle = document.querySelector('head');let setFavicon = document.createElement('link');setFavicon.setAttribute('rel','shortcut icon');setFavicon.setAttribute('href',favImg);headTitle.appendChild(setFavicon);}setFavicons(fav);`

### Instantly Play Vine BOOM Sound Effect
##### `javascript:var audio = new Audio("https://cdn-eu-hz-6.ufile.io/get/lms6joof?token=YmQ1NDZhMDQ1ZTBlZDk1NTFkNDA4YWM5MmM1Y2E2YjY0ZDU4ZmU4MjhjMDNhNDc2ODQ0YTFjMjYzNDVmMGE5MmEzOTE5OGI1N2Y4YjUxZTU3MDM3YmY2ZWMwZGU3ZjdlOTY2OGUzOTE1YjcyNmI2NjhmNGY0ZGIyNjY0MzY2NTc3VVhTTGRIaDZQbWEyNlVCd2RoTjhxRzFuaitHc3ZsTlAzN0w4MERDVmZyMGhhQ0IwOWlZdTQrVXFuYStFR1d1YWkrL2dRRXNMZmRzbWVIZ0lqK205N1RYT3NadDE3eUFhVlNhcm5GaXpQdEJjUHVLYUdGOVI5VjZnYTRKdjZQc285Vml0d2tQdEw1Zmlub0V1UTJPMWlFdTMzOGMzNHp5OW5HTFE2QWJZbWtBT0EzY0wvRkJhY1ZYYklLUlpvRW53WG1vRkdubDdrV2dQRXJ0aGV4ZFBFZjVybGZnVjNIdkpNVlJjUWJlZGNlVUZwOVUxcGpLTjMzQ3lHdEpsWDZK");audio.play();`

## To get more of these inport the "tools" bookmark file above
