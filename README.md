# ping_host

What is a ping?

A ping (Packet Internet or Inter-Network Groper) is a basic Internet program that allows a user to test and verify if a particular destination IP address exists and can accept requests in computer network administration. The acronym was contrived to match the submariners' term for the sound of a returned sonar pulse.

Ping is also used diagnostically to ensure that a host computer the user is trying to reach is operating. Any operating system (OS) with networking capability, including most embedded network administration software, can use ping.

For example, to find the dot address, such as 205.245.172.72, for any given domain name, Windows users can go to the command prompt screen (start/run/cmd) and enter ping xxxxx.yyy, where xxxxx is the second-level domain name, like "whatis," and yyy is the top-level domain name, like "com."


# Installation


apt update && apt upgrade -y

pkg install git

pkg install python

pkg install python2

pkg install python3

git clone https://github.com/SCSEA/ping_host.git

cd ping_host

chmod +x *

python3 ping_host.py
