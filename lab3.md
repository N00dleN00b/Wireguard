# Project 3 Docker
## by Bristie Rahman

### step 1
first I created an account of digitalocean.com using the special link in the slides to redeem 200 dollar free credit. 
Then I created a droplet where I followed the instruction below to install docker / wireguard

(This resource was followed:)
>https://thematrix.dev/setup-wireguard-vpn-server-with-docker/ 

>https://docs.docker.com/compose/install/

For Docker in brief:
Had it already installed on my windows from the previous project so I used that resource to my advantage.

For Wireguard in brief:
This one however was completely new but using the source was pretty smooth sailing. 
First basically after opening up the droplets kernel/shell I made a directory for the wireguard/config where I made a .yml file where I copied and pasted the contents from the online guide. 

Then after having the file up and running, (editing the timezone and personal ip) I had to connect it to my phone.
### step 2
After installing both docker and wireguard I had to prove connection using the vpn. I was first able to test this by downloading an app on my phone. 

This app was called Wireguard. I hit the command that created QR codes based on the peers I edited. After clicking the plus button on my phone I scanned the QR code created from my laptop kernel. Once I had the vpn set up I had to show the difference between the vpn being on and seeing what changes on IPLeak.net in a browser (also on my phone that was a mistake I kept running into).
### step 3
Finally I had to check the VPN connection on my laptop. This was done by also installing wireguard on my laptop. Where I copied the .conf files from my kernel to wireguard application itself. Then in a similar fashion revisited IPleak.net checking how it looked with and without the vpn running. 

The steps weren't too much for this lab but there are a lot of screenshots I had to do which I will share through harvey and github!