<h1>Weather Panel</h1>
Weather Panel displays inside and outside temp and weather infomation as a web page. Also has a random customizable background serviced by Dropbox public folders.<br>Once installed use the link to run it as a webapp on Andriod, IOS, or any desktop browser. On Andriod devices i highly recomend using "Full Screen Browser" from the Play Store to get rid of the navigation and status bars. (https://play.google.com/store/apps/details?id=tk.klurige.fullscreenbrowser)<br>
<img src='http://sidjohn1.github.io/smartthings/WeatherPanel/screenshot1.gif'>
<h2>General FAQ:</h2>
See: https://github.com/sidjohn1/smartthings/blob/master/README.md#faq<br>
<b>If the installation steps arent clear this is a good place to start.</b>
<h2>Instalation</h2>
<ol>
  <li>Copy the code from weatherpanel.groovy into a new smart app</li>
  <li>Besure to enable OAuth</li>
  <li>Install the Weather Panel smartapp in the smartthings app </li>
  <li>Select Inside/Outside Temp Devices</li>
  <li>Select View URL and copy the URL into a broswer</li>
  <li>IOS or Android: Install webapp from browser<br>Android: Run URL in Full Screen Browser *Reccomended for Android*</li>
</ol>
<h2>How to use your own Dropbox Account:</h2>
<ol>
  <li>Login into your dropbox account and ensure you have a Public Folder</li>
  <li>Enable your Public Folder with this link</li>
  (https://www.dropbox.com/enable_public_folder)
  <li>Create a Wallpaper folder inside your Public Folder</li>
  <li>Upload some pictures to your Public > Wallpaper folder</li>
  <li>Select a picture and click "Copy public link"</li>
  (http://sidjohn1.github.io/smartthings/WeatherPanel/dropbox1.png)
  <li>Copy the number after "/u/" and before "/Wallpaper/". This is your Dropbox Public UID</li>
  (http://sidjohn1.github.io/smartthings/WeatherPanel/dropbox2.png)
  <li>Create a file called index.json in your Public > Wallpaper folder</li>
  Mac Users can use (create-index.json.sh) to automate the process<br>
  Windows Users can use (http://sidjohn1.github.io/smartthings/WeatherPanel/index1.json) or (http://sidjohn1.github.io/smartthings/WeatherPanel/index2.json) as an example. Replace 00-05.jpg with the actual filename and add addition entries as needed. Just be sure there is no "," after the last "}".
</ol>


