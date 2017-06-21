<b>Installation</b>

Download and extract ZIP file to [yourfolder]

If you haven't already installed Node.js, visit the site below 

https://nodejs.org/en/download/

next, open terminal or cmd and install the http-server module globally on your machine

npm install http-server -g

run it using CLI (specifying the folder you'd like to serve files from)

http-server ./[yourfolder] -p 1337
now you should be able to access your files (via something like http://localhost:1337/myfile.html) in a web browser.
