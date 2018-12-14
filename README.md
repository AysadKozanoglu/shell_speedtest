### download speedtest on shell ###


the script take the nearest server to test the speedtest 
<pre>
wget -O speedtest https://git.io/fpbus && chmod +x speedtest && ./speedtest

OR

wget -O - https://git.io/fpbus | python
</pre>

## output like ##
<pre>
Retrieving speedtest.net configuration...
Retrieving speedtest.net server list...
Testing from NetCologne GmbH (xx.xxx.xx.xxx)...
Selecting best server based on ping...
Hosted by dataroute (Dusseldorf) [33.13 km]: 11.683 ms
Testing download speed........................................
Download: 88.52 Mbit/s
Testing upload speed..................................................
Upload: 9.58 Mbit/s
</pre>

