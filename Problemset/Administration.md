# Administration

## Problem Statement

1. You have a file with passwords in it on your PC. Every 3 hours, you add a new password to the file. The format of the file is something like this:

```txt
S.No. WEBSITE       USERNAME          PASSWORD

1.    github.com    someuser          somepass
2.    google.com    anotheruser       anotherpass
```

  As you see, this file has some very confidential information which you don't want to lose at any cost. Since your friend are also engineers, they can easily find it in your PC if they have access to your PC. Also, consider scenarios such as your hard-disk goes corrupt and you can lost the data anytime. Come up with a solution as to how you can store all this information safe for the maximum amount of time. Also consider that you have to regularly update this file so updating the file should also be easy. The more robust and secure your solution is, the more you score.

2. Censorship on the internet is a pain which we all go through. While we here are thinking what we should do about censorship in our institute, another group of people was writing code to make this happen, and hence made [`streisand`](https://github.com/StreisandEffect/streisand): <https://github.com/StreisandEffect/streisand>. This group of people made this awesome open source software which can be used to break through all the restrictions. The software they made can be installed on any set of remote server, for instance on the [AWS(Amazon web services)](https://aws.amazon.com/) server, or [digitalocean droplets](https://www.digitalocean.com/) server. These are nothing but remote computers which you can buy and use for yourself. You even get free to try, for instance you get [750 hours of Amazon EC2(EC2 is the amazon name a server or computer) for free](https://aws.amazon.com/free/) which is approximately 30 days. Digitalocean charges $5 (Rs. 320) for 1 month for 1 virtual PC with 1 GB ram.

Your task is very simple. You need to signup on AWS / Digitalocean / some other virtual server providing company and install `streisand`. Then you need to ***SETUP YOUR OWN VIRTUAL PRIVATE NETWORK(VPN)*** according to the instructions given on the streisand github page. All the supported virtual server providers are given on the [streisand github page](https://github.com/StreisandEffect/streisand). Choose whatever you like.

**NOTE:** If you go with any of the virtual machine providers, remember to switch off the servers when not in use, else you may face additional charges.

## Weightage

1. 50 points
2. 150 points

## Deliverables

In your git repository whose link you will be submitting, make a folder `Administration` with 2 file in it:

1. `README.md`: Here you need to report your findings, how you did this, what all resources you took help from, and what you learnt.
2. `VPNSetup.md`: This should contain the steps required for anyone to use your VPN. For instance, we use `SurfEasy` or `Psiphon` as a VPN in our smartphones. We need to be able to connect any device, either a smartphone or a PC, with your custom VPN.

Remember, do not worry if you are unable to complete it, just document whatever you were able to do. :) 
