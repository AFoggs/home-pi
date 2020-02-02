# Home Pi Performance Server

After purchasing a Raspbery Pi, I decided that I wanted to work on some projects that improved the quality of my internet use at home. There was no need to do anything major, rather I focused on fixing a few minor pain points in my life.

I focused on what was important to me: improving security, upgrading my home network speed, and increasing accessibility. With these things in mind, I set out to complete this: Ad-blocking at the network level, Home VPN access, and Remote Access to my Raspberry Pi, with both GUI and Non Gui Options.

# Table of Contents

1. [Ad-Blocking](#ad-blocking)
2. [VPN Access](#vpn-access)
3. [Remote Access - GUI](#remote-access---gui)
4. [Remote Access - Terminal](#remote-access---terminal)
5. [Updates](#updates)

## Ad-Blocking

One of the most painful parts of browsing the internet while at home is ads. Of course, it's nice that they are personalized, and sometimes they are actually pretty useful, showing us products that we weren't even sure we wanted, but the vast majority of the time, they are annoying.

Thankfully, someone had already come up with a solution: [**Pi-Hole**](https://docs.pi-hole.net/guides/vpn/installation/)

It is open source and easy to set up, and it blocks ads at the domain level. It is only heightened by Pairing it with a VPN.

## VPN Access

The nice thing about the Raspberry Pi is the amount of support it receives. As such, there are a lot of different Open Source Softwares that have been tailored to it.

As such, [**Pi-VPN**](https://pivpn.dev/) was created. Based on OpenVPN, it makes for a great use to create a home vpn server. It's free, and it allows you to protect yourself while you are in public-- or if you need to access any local files from home.

Combined with Pi-Hole, this allows ads to be blocked ads even while connecting to the VPN through 4G LTE or other methods.

## Remote Access - GUI

Though the raspberry pi is now setup, there may be some times where you want to access the machine. I have my Pi completely disconnected from a monitor itself. And though I have no need to utilize it's GUI interface, there are times where I may want to for whatever purpose.

Thankfully, [**Real VNC Viewer**](https://www.raspberrypi.org/documentation/remote-access/vnc/) has a raspberry pi distrubution that is free. It is just like Team Viewer, but specifically for linux systems.

## Remote Access - Terminal

Unless you are using a linux machine as your primary one, I recommend [**PuTTY**](https://www.putty.org/). Don't expose your raspberry pi to the network by opening another port. Instead, connect to the VPN and utilize PuTTY from there, so do take note of the ip address of your raspberry pi.

## Updates

Currently, this is my raspberry Pi Set Up that improves my overall performance. I may add additional updates if I change my setup.
