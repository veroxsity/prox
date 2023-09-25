# prox
This app is a useful one as it turns a list of proxies into a list of working proxies that can be used for any app.

1. Head to https://https://free-proxy-list.net/# and then copy the raw ip list.
2. Paste the proxy list into proxies.txt
3. Run Prox.exe and wait for it to test the proxies
4. Then run BestProxyFinder.exe and it will narrow the proxies down to 10
5. Then run Downloader.exe to get the different games/apps.
   
When running prox.exe, it will add "http://" to every proxy in your list and then test them all. Once all are tested
it will then remove any that don't work and there you go, you have a list of working proxies to be used on any app.

Additionally, you can run BestProxyFinder.exe, and it will narrow all of the proxies down to the 10 with tbe best
download speeds.

When running Downloader.exe, it will download a list of Available downloads and shows a number corresponding to them.
Type your number and then the program will start to download and unpack your selected item. If a proxy crashes, the
program will automatically try a different proxy to be used for the download.

****proxies.txt MUST be in the same directory as Downloader.exe otherwise your download will not start****
The download will be downloaded and unpacked to the current directory so start it in the place that you want it to 
avoid broken configuration files.

There are 2 ways to fix a slow download speed, however they might not work depending on your connection.
1. restart Downloader.exe and try again.
2. Redo the proxy list. (Prox.exe and BestProxyFinder.exe)
   
If they don't work then your download speed is stuck being slow.
