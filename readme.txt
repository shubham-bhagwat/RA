Instructions-
The shell script is to extract dns/tls records from raw pcap files and
python script is to extract domain name (and their time epoch) from dns/tls records.

Access to thels
 lab server, using 
ssh shubham@129.10.227.207

You can find the network traffic for each device in this directory:
/traffic/by-name

Inside the directory of every device you will find some files containing misc information (such as the mac address).
What you need is the content of the directory "unctrl", which contains many "pcap" files, organized by date, for when the device actually produced network traffic.

shell script needs an input file with list of devices
python script needs the list of pcap file you’re analyzing as the input.

You can find the device file here: /traffic/devices.txt

run the shell script on the mon(iot)r server.
But for the python one, it would be better to run it on your local machine. You can use scp to copy files to your computer.





dircetory name-
/traffic/by-name/google-home-mini/unctrl

file format-
2021-08-25_17.23.33_192.168.10.117.pcap

88:de:a9:8:3:b9 roku-tv

d4:a3:3d:6b:1e:97 homepod

20:df:b9:5f:41:7e google-home-mini

