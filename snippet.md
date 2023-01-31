<div style="position:relative; width:234px; height:60px;">
  <a id="tm_link" href="https://download.teamviewer.com/full" style="text-decoration:none;">
    <img src="https://static.teamviewer.com/resources/badges/teamviewer_badge_flat4.png" alt="TeamViewer pour Télé-assistance" title="TeamViewer pour Télé-assistance" border="0" width="234" height="60" />
  </a>
</div>
    
var is_OSX = /(Mac)/i.test(navigator.platform);
var is_iOS = /(iPhone|iPod|iPad)/i.test(navigator.platform);
var is_ANDROID = /(Android)/i.test(navigator.platform);
var is_WIN = /(windows)/i.test(navigator.platform);
var url_android = "https://play.google.com/store/apps/details?id=com.teamviewer.quicksupport.market";
var url_ios = "https://itunes.apple.com/us/app/teamviewer-quicksupport/id661649585";
var url_mac = "https://download.teamviewer.com/download/TeamViewerQS.dmg";
var url_window = "https://download.teamviewer.com/download/TeamViewerQS.exe"

if (is_OSX) document.getElementById("tm_link").href = url_mac;
if (is_iOS) document.getElementById("tm_link").href = url_ios;
if (is_ANDROID) document.getElementById("tm_link").href = url_android;
if (is_WIN) document.getElementById("tm_link").href = url_window;
