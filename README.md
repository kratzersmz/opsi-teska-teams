# opsi-teska-teams
Get Teams unpacked Files...(installer seems to to do what we need)

start Teams msi(so it unpacks the installation)
go to %appdata%\Local\microsoft teams and copy alle files to teams directory on the opsi server

<code>
ls -t
dirlist   app.ico                Resources.pri                      setup.json
packages  SquirrelTelemetry.log  Update.VisualElementsManifest.xml
current   SquirrelSetup.log      Update.exe
</code>


