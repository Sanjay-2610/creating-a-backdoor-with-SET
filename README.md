# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![272870788-098c0b3a-88d0-49e8-a20a-9e3e8338f704](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/f27abddc-1d57-44d9-95d7-c2cae15a601e)
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:


It displays the following menu and select 2 for Website Attack Vectors:

![272870942-3bb4c127-f934-4936-b6aa-090c25fa4182](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/d98e346d-28be-452f-bffa-ceafe4e5857e)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![272871084-b18ab1dc-30b7-4ae1-9d4e-2eda273e46bf](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/c773645d-2c45-475e-ac1b-7a5dbce3746c)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![272871364-117814d4-f8b6-4479-bcf4-25634df85b17](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/c1529170-f9e2-43e8-9c77-831cfc2c0ec2)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![272871507-248aac47-e77a-4f2e-940a-4af024cdba97](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/be552718-7fcb-4bcb-a183-50a7090c22c0)


It shows the following screen in which the option Google can be selected:
![272871651-fea864fe-011d-472b-9e99-19ba7204633b](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/3c32e1d8-271b-4d3d-b1c8-7b0f867738c1)



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![272871802-2a0ac6ae-95fd-4d70-98a9-7066ad5fb78f](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/05ac0352-a375-4e3f-b2ae-4d30998d9106)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![272873738-c9389e65-2183-4967-a426-a48a0beb661e](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/28d50489-0f73-4ca1-b238-fbc22458d100)



SET logs the information regarding the Google credentials:
![272871972-31b58a4f-e4d8-4739-8ffa-2597bb82c4e8](https://github.com/Sanjay-2610/creating-a-backdoor-with-SET/assets/91368803/5badcb0f-6a23-4d63-b3d4-3fcbc302fb51)


SET logs the information in the xml file under /root/.set directory:



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
