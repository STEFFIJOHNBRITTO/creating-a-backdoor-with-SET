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
## OUTPUT

<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_20_26" src="https://github.com/user-attachments/assets/a5b348b5-c468-4220-8afc-d2db9e959128" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_20_26" src="https://github.com/user-attachments/assets/17e21401-738f-45fc-916f-e558472ddfb4" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_20_39" src="https://github.com/user-attachments/assets/34cc8b7a-2eff-4a2e-a148-954da4752807" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_20_49" src="https://github.com/user-attachments/assets/f3ef5411-dc13-44a0-b84f-713643e2d246" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_21_10" src="https://github.com/user-attachments/assets/4f9e8e00-124a-4762-b991-1a47210217f0" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_27_12" src="https://github.com/user-attachments/assets/1a93ebcd-c59e-4293-a1b9-9bfa73e34e5a" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_27_28" src="https://github.com/user-attachments/assets/de54dc03-fd70-400f-8bfd-d124e4664c09" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_27_28" src="https://github.com/user-attachments/assets/de54dc03-fd70-400f-8bfd-d124e4664c09" />

SET logs the information regarding the Google credentials:
## OUTPUT


<img width="1920" height="1065" alt="VirtualBox_kali_21_05_2026_09_38_21" src="https://github.com/user-attachments/assets/11680ed7-7bb0-4853-aa4f-81108df9841e" />















## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
