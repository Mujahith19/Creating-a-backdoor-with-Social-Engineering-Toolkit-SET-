# Experiment-07-Creating a backdoor with Social Engineering Toolkit

##  AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
1) Install kali linux either in partition or virtual box or in live mode
2) Investigate on the various categories of tools as follows:
3) Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 

The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/72911488-bd84-487d-b87b-fb13a107dd1e)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/0c19e322-a942-4cc1-99ed-b8455da43abf)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/9548d003-27a3-4509-bd8d-b38967e27fc3)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/a6760b9d-8632-47ce-b295-9699e54f3a33)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/ab2f001d-d317-48cd-acb5-9de51c191fdc)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/7c15a2f5-9da0-49cf-a269-d57e411f8539)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/fc3120cc-0342-4a95-b2a6-d1951daf3219)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/1fb0bc90-0220-4dde-9aae-2cabc3873291)

SET logs the information regarding the Google credentials:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/9457e41a-31e2-48a7-88d0-7c71afb30367)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/Monisha-11/creating-a-backdoor-with-SET/assets/93427240/3c288818-d232-4d31-b09f-a1db311cbd94)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully.
