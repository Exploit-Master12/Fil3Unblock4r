# Fil3Unblock4r

Go to 
```
https://extwifi.playcode.io/
```
And then click "Skip intro".
You can play around with the "proxy" and the "CyberSamurai Wifi generator"
but the main deal I want to show you today is the middle part:
The cloaked file site generator.

Follow the directions there.

But in the first part,the "Enter URL for iframe",copy-paste this code that I made in:

```
data:text/html;charset=utf-8,<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8" /> <meta name="viewport" content="width=device-width, initial-scale=1.0" /> <title>Google Iframe VPN</title> <link rel="manifest" href="manifest.json" /> <script> if ("serviceWorker" in navigator) { navigator.serviceWorker .register("/sw.js") .then(() => console.log("Service Worker Registered")) .catch((err) => console.error("Service Worker Error:", err)); } let deferredPrompt; window.addEventListener("beforeinstallprompt", (e) => { e.preventDefault(); deferredPrompt = e; document.getElementById("install-btn").style.display = "block"; }); function installPWA() { if (deferredPrompt) { deferredPrompt.prompt(); deferredPrompt.userChoice.then((choice) => { if (choice.outcome === "accepted") { console.log("PWA installed"); } deferredPrompt = null; }); } } </script> </head> <body> <h1>Blobbypass 2.0 <iframe src="https://www.google.com/webhp?igu=1%22%20width=%22100%%22%20height=%22600px%22%20style=%22border:%20none%22%20%3E%3C/iframe%3E%20%3Cbutton%20id=%22install-btn%22%20onclick=%22installPWA()%22%20style=%22display:%20none%22%20%3E%3C/button%3E%20%3C/body%3E%20%3C/html%3E%20Install%20Button%20and%20Unblocked%20iframe%20made%20by%20Viaan%20Gothivrekar%20%3Ca%20href=%22https://github.com/Exploit-Master12%22%20target=%22_blank%22%20%3E(Exploit-Master12%20on%20Github)%3C/a%20%3E
```
And now go to a nwe tab,and click Control+O.
Select the file you just made,which should be called,"Cloakedsite.html".
Select it and click "Open".

Behold: You did it!

**How it works** 
Most schools don't block files (Of course they don't,It would crash  the computer if they did,lol)
So,I figured,why not make a Google Iframe VPN website and put the code in a data: url?
Then,I thought,Many schools block "data:text:HTML" websites,so they block it.
Now,see here,when I put a URL like that in a file creator,it HAS to come up as a google.
Because it's a file,the extension does not show on a file.
So,yes,it works.

Follow for more exploits, Exploit-Master12  🙂 =-)

