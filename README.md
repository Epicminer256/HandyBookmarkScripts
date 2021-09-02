# HandyBookmarkScripts
### Here are 17 bookmark scripts (or they are called "bookmarklet") you can use on Chrome/ChromeOS. Some of these include Tab Hiders, Inspect Element (even if it is blocked), Soft/Hard reset, SoundBoard without going to any website, WiFi login portal detection, and others

# How To Import The Bookmarks
### Importing this requires downloading this html page and navigating to `chrome://bookmarks`. On the three dots to the top right hit import and select the html file. Move the "Tools" folder to the root of your bookmarks.


# Fun facts
### Ctl+Shift+B Hides/Shows the bookmark bar and Shift+Alt+B focuses the Bookmark bar and allows you to use your arrow key and the enter key to navigate it. Mastering this can allow folders and subfolders to be browsed though easly and can keep your bookmarks clean looking

[Drag Me To Your Bookmark Bar for a lite version!](javascript:void%20function(a){var%20b=function(a){function%20b(){document.getElementById(%22contextMenu%22).style.display=%22none%22}a(document.body).append(`
%20%20%20%20%3Cstyle%20type=%22text/css%22%3E
%20%20%20%20%20%20%20%20.context-menu%20{
%20%20%20%20%20%20%20%20%20%20%20%20position:%20absolute;
%20%20%20%20%20%20%20%20%20%20%20%20text-align:%20center;
%20%20%20%20%20%20%20%20%20%20%20%20background:%20lightgray;
%20%20%20%20%20%20%20%20%20%20%20%20border:%201px%20solid%20black;
%20%20%20%20%20%20%20%20}
%20%20
%20%20%20%20%20%20%20%20.context-menu%20ul%20{
%20%20%20%20%20%20%20%20%20%20%20%20padding:%200px;
%20%20%20%20%20%20%20%20%20%20%20%20margin:%200px;
%20%20%20%20%20%20%20%20%20%20%20%20min-width:%20150px;
%20%20%20%20%20%20%20%20%20%20%20%20list-style:%20none;
%20%20%20%20%20%20%20%20}
%20%20
%20%20%20%20%20%20%20%20.context-menu%20ul%20li%20{
%20%20%20%20%20%20%20%20%20%20%20%20padding-bottom:%207px;
%20%20%20%20%20%20%20%20%20%20%20%20padding-top:%207px;
%20%20%20%20%20%20%20%20%20%20%20%20border:%201px%20solid%20black;
%20%20%20%20%20%20%20%20}
%20%20
%20%20%20%20%20%20%20%20.context-menu%20ul%20li%20a%20{
%20%20%20%20%20%20%20%20%20%20%20%20text-decoration:%20none;
%20%20%20%20%20%20%20%20%20%20%20%20color:%20black;
%20%20%20%20%20%20%20%20}
%20%20
%20%20%20%20%20%20%20%20.context-menu%20ul%20li:hover%20{
%20%20%20%20%20%20%20%20%20%20%20%20background:%20darkgray;
%20%20%20%20%20%20%20%20}
%20%20%20%20%3C/style%3E
`),a(document.body).append(`
%20%20%20%20%3Cdiv%20id=%22contextMenu%22%20class=%22context-menu%22%20
%20%20%20%20%20%20%20%20style=%22display:none%22%3E
%20%20%20%20%20%20%20%20%3Cul%3E
%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3E%3Ca%20href=%22javascript:(function%20()%20{var%20script=document.createElement('script');script.src='https://x-ray-goggles.mouse.org/webxray.js';script.className='webxray';script.setAttribute('data-lang','en-US');script.setAttribute('data-baseuri','https://x-ray-goggles.mouse.org');document.body.appendChild(script);}())%22%3EInspect%3C/a%3E%3C/li%3E
%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3E%3Ca%20href=%22javascript:var%20title%20=%20prompt(%26quot;Title%3F%26quot;,%20%26quot;Home%20|%20Schoology%26quot;);document.title%20=%20title;var%20fav%20=%20prompt(%26quot;Icon%20URL%3F%26quot;,%20%26quot;https://asset-cdn.schoology.com/sites/all/themes/schoology_theme/favicon.ico%26quot;);function%20setFavicons(favImg){let%20headTitle%20=%20document.querySelector('head');let%20setFavicon%20=%20document.createElement('link');setFavicon.setAttribute('rel','shortcut%20icon');setFavicon.setAttribute('href',favImg);headTitle.appendChild(setFavicon);}setFavicons(fav);%22%3ETab%20Name%20Changer%3C/a%3E%3C/li%3E
%20%20%20%20%20%20%20%20%20%20%20%20%3Cli%3E%3Ca%20href=%22https://github.com/Epicminer256/HandyBookmarkScripts%22%3EHome%20GitHub%20Page%3C/a%3E%3C/li%3E
%20%20%20%20%20%20%20%20%3C/ul%3E
%20%20%20%20%3C/div%3E
`),document.onclick=b,document.oncontextmenu=function(a){if(a.preventDefault(),%22block%22==document.getElementById(%22contextMenu%22).style.display)b();else{var%20c=document.getElementById(%22contextMenu%22);c.style.display=%22block%22,c.style.left=a.pageX+%22px%22,c.style.top=a.pageY+%22px%22}}};if(a%26%26a.fn%26%261.7%3C=parseFloat(a.fn.jquery))return%20void%20load(a);var%20c=document.createElement(%22script%22);c.src=%22https://ajax.googleapis.com/ajax/libs/jquery/1/jquery.js%22,c.onload=c.onreadystatechange=function(){var%20a=this.readyState;a%26%26%22loaded%22!==a%26%26%22complete%22!==a||b(jQuery.noConflict())},document.getElementsByTagName(%22head%22)[0].appendChild(c)}(window.jQuery);")
