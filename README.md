# ProxmarkRDV4-ParrotOS
## Parrot OS installation instructions

This tutorial has been created by following the [RFID research group](https://rfidresearchgroup.com) instructions for ubuntu. I am using the instructions based on ubuntu, as it is a Debian based system, which is the foundation for the Parrot OS. As there are no other tutorials out there for ParrotOS, I am going via this route for now. I've also taken a look at some other blogs and the github repo's and brought in where I could the useful parts which help the process.  There is also a video for full installation to help guide you. 

If you want to head straight to the Installation head to [Installation](Parrot-OS-Proxmark3-RDV4-installation.md) but the below will give you some further information which may come in handy to know.

## Background:
This is the 2nd editorial and video I have done for the RDV4 installation, the first one, I showed to Iceman and being the legend, that he is, he has now kindly made changes to the GitHub repo based on some of the points I had made in the first video. He set to work straight away and now the GitHub repo is better than ever. 
The readme has been updated and some updates have been made to the [official repo](https://github.com/Proxmark/proxmark3) also.
Just to note, the official repo has installation instructions for different operating systems within its [wiki pages](https://github.com/Proxmark/proxmark3/wiki), which you could perhaps use but I have opted for the [RFID research group repo](https://github.com/RfidResearchGroup).

## Why the RFID Research group repo?
I opted to go for the RFID research group produced by Iceman as it seems to be the best fit for the RDV4 as it supports all the new features with the new hardware.  They created the R[RFID research group repo](https://github.com/RfidResearchGroup) specifically for the RDV4 so not to muddy the waters with the office Proxmark3 build. 
There is also a iceman fork on github, this is not to be confused with the RFID Research group build.
The iceman repo is a bleeding edge pull from the official proxmark3 repo, it's different in its command and style. The RFID research group repo is based on the iceman build, but is focused on the RDV4 hardware and is a stable build. 

## Issues
If you do have issues, fall back to the Proxmark 3 official repo for [Ubuntu](https://github.com/Proxmark/proxmark3/wiki/Ubuntu-Linux). Over time further features and code improvements are being implemented in the Proxmark3 repo.
I have researched into the different repos and the dependencies required. There is some overlap but some differences between the official Proxmark 3 repo for Kali and Ubuntu, and the RFID Research group Kali and ubuntu. With ParrotOS being based on Debian, logic would state any of these may work and could probably cover most debian based systems. However due to the dependencies being different you may experience issues with the build if you opt for another repo. 

## Other resources to look at
The video tutorials are thin on the ground when it comes to the RDV4
There is a good overview on [unlocking the secrets of the proxmark3 RDV4](https://rfidresearchgroup.com/2018/11/21/blackalps-2018-unlocking-secrets-of-the-proxmark3-rdv4-0-christian-herrmann-and-kevin-barker/) which talks about the functionality of the new RDV4 and the improvements made since the last edition if you want to get some background. 
And there is also a [RDV4 unboxing video](https://www.youtube.com/watch?v=aqS-QsuFFTU) which covers what is provided within the kickstarter pack I purchased. In this video myself and sharka cover some differences to the rdv2 but mostly go into the components and what we thought at first look. 
Tinker has created a blog post which covers some of the details around the lights and what they mean and how to use the Proxmark in standalone mode. Provides some images and some tips which can be found [here](https://www.tinker.sh/badge-cloning-clone-hid-prox-with-proxmark3-rvd4/)
Iceman has also done an update with the leds  ie.  on older proxmark3 devices the leds RED and YELLOW lights up,  while on RDV4 its leds are A and C and all leds on rdv4 are red.  Only the power leds are blue.

