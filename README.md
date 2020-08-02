# Network_based_scripts
I have included the scripts to perform the following functions
* **MAC address changing**
* **Code injecion**
* **DNS Spoofing**
* **Download lazagne**
* **Keylogger and reporting via e-mail**
* **Network Scanning** 
* **Replacing Downloads** 
* **ARP Soofing**
## Description
#### MAC Address changer
This programme can be used to change the MAC address i.e. the pyhsical address of your device as visible to other users on your current network. The interface can be chosen by the user for which the change is desired.
#### Code Injector
This programme can be used to inject mallicious code in the response received from the server of a website. The code was tested successfully for the following piece of code `<script>alert('test');</script>`
#### DNS Spoofer
DNS stands for Domain Name System. This programme can be used to redirect a user to differnet URL when a particular Domain Name/URL is requested.
#### Download Lazagne
**Lazagne** is a post exploitation tool generally used to render saved passwords on the target computer. But I have added a mailing feature in the programme which allows Lazagne to work as a pre exploitation tool by sending the saved passwords on a desired e-mail in a text file. Also the programme atomatically deletes after carrying out the desired operation.
#### Keylogger
The programme can be used to record every key strike on the target computer and also send the results to a desired email in a text file.
#### Network Scanner
The programme can be used to  find out other devices connected on your current network. It provides information of their Internal IP Adresses as well as MAC Adresses
#### Replacing Downloads
The programme can be used to replace downloads for a target computer by a malicious file on the fly.
#### ARP Spoofer
ARP stands for Address Resolution Protocol. This protocol is used to resolve MAC Address for a given IP Adress. This programme allows you to run a basic Man In The Midddle Attack by altering the ARP Tables of both the target and the Router. On Completion of the task the ARP tables are restored.



>NOTE
* Sripts such as DNS Spoofer, Code Injector and Repalce Downloads can only be used for HTTP websites. For websites that use HTTPS SSL STRIP can be used along with the following scripts. For more info : https://github.com/moxie0/sslstrip
* For more info on Lazagne: https://github.com/AlessandroZ/LaZagne
