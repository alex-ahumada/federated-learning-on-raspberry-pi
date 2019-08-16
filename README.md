# Federated Learning with Raspberry PI (PySyft)
Scholars from the Secure and Private AI Scholarship Challenge from Facebook and Udacity working together to implement the tutorial from OpenMined: https://blog.openmined.org/federated-learning-of-a-rnn-on-raspberry-pis/

We will set up PySyft on two Raspberry Pis and learn how to train a Recurrent Neural Network on a Raspberry Pi via PySyft.

## Topics
   - PySyft(https://github.com/OpenMined/PySyft)
   - Raspberry Pi

## Project lead
- Shashi Gharti - https://github.com/shashigharti
- Helena Barmer - https://github.com/helenabarmer

## Contributors/Team
- Jess - https://github.com/jess-s
- Nirupama Singh - https://github.com/nirupamait
- Pooja Vinod - https://github.com/poojavinod100
- Alex Ahumada - https://github.com/projectsperminute
- Elena Kutanov - https://github.com/EVikVik
- Mahmmoud Mahdi (qursaan) - https://github.com/qursaan
- Ayesha Manzur - https://github.com/GlowWorm95
- Ivoline Ngong (Ivy) - https://github.com/ivyclare
- Nachiket - https://github.com/nachiket273
- Joyce Chidiadi - https://github.com/Joycechidi
- Temitope Oladokun - https://github.com/TemitopeOladokun
- Shivam Raisharma
- Sankalp Dayal - https://github.com/sankalpdayal5
- Sushil Ghimire
- Oudarjya Sen Sarma
- Juan Carlos Kuri Pinto
- Vigneshwari
- cibaca
- Oluwadamilola Saka (Dammy)
- Molly ngampit
- Ebinbin Ajagun - https://github.com/meajagun
- Ankur Bhatia
- Suparna S Nair - https://github.com/suparnasnair
- Sayed Maheen Basheer - https://github.com/SayedMaheen
- Sergio Valderrama - https://github.com/vucket
- Stanislav Ladyzhenskiy - https://github.com/LStan
- Mikaela Sanchez - https://github.com/mikaelasanchez
- Muhammad Naufil - https://github.com/mnauf

## Start Contributing
The tutorial on how to contribute can be found here. https://github.com/shashigharti/federated-learning-on-raspberry-pi/wiki/How-to-contribute

## Getting Started:
## Project Equipment Setup
This project requires the following equipment:
# 1. Raspberry PIs:
-- > 2 Raspberry PIs 3 B+ running Raspbian Stretch 4.14
-- > The PIs are connected to the internet via Ethernet cables.
-- > Each PI has its own static IP(Internet Protocol) address.

# 2. Laptop or Desktop:
-- > The laptop or desktop machine is running Ubuntu 18.04 LTS and connected to the same LAN where the Raspberry PIs through a switch.

# 3. Ethernet Port
A TP-Link 5-Port Ethernet Switch was used

## Libraries and Dependencies
The following are the major python libraries and dependencies used in the project
1. Install Python 3.6.7 which is the version that seems to be compatible and more stable with PySyft and PyTorch at the moment.
2. Install PyTorch 1.0.0
This section proves difficult and took several hours to complete. Some of the project members had the experience where their installation got stuck or even crashed halfway through. Before installing PyTorch a swap file was created. Then install PyTorch.
3. Install PySyft and its dependencies
## How to get Started
1. Download Rasbian Buster (the latest Raspbain image), which comes with pre-installed python 3.7.3: because older version of rasbian comes with python 3.5, and we have to install python 3.6.7 or higher separately.
Download: https://www.raspberrypi.org/downloads/
You can either choose NOOBS are Raspbian, I would recommend to go for Raspbian.
![Screenshot](https://imgur.com/DmcyN9E.jpg)
2. Choose your favorite image burner. I personally use Etcher
Download: https://www.balena.io/etcher/
![Screenshot](https://imgur.com/11eMRnn.jpg)
After installing, it looks like this
![Screenshot](https://imgur.com/pbxmRO3.jpg)
3. Get an SD card reader. Insert your SD card in it. Plug in your machine(laptop/computer). Open Etcher, select the Raspbain Buster newly downloaded file(image). Select the SD card, you want to install(burn) raspbian in. Click Flash. It takes around 5 mins to install. Then eject the SD card reader. Take out SD card from it, and insert it in your Raspberry Pi and tadaa congrats you have an economical desktop computer :D


