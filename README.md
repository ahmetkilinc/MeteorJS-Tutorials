# MeteorJS-Tutorials

How to install (Windows):

1- install chocolatey:
  Open cmd as administrator
  run this command: @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
  
2- install meteor:
  choco install meteor
  
3- create new meteor app:
  meteor create newAppName
  
4- remove blaze html templates: (if you dont want to use blaze as a template language)
  meteor remove blaze-html-templates

5- add angular templates: (if you desire to use Angular. You can use React or Vue, too.)
  meteor add angular-templates
