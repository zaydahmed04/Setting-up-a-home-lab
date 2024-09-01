# Setting up a homelab

## Objective

The Home Lab project aimed to create a controlled environment for simulating and defending against cyber attacks. The focus was on using Kali Linux to launch attacks on an Ubuntu VM, while employing UFW for defense and analyzing network traffic with Wireshark. This hands-on experience was designed to enhance understanding of cybersecurity tactics, attack methods, and effective defense strategies.

### Skills Learned

- Proficiency in setting up and managing virtual environments.
- Practical experience in penetration testing with Metasploit.
- Advanced skills in network traffic analysis using Wireshark.
- Ability to implement and configure firewall defenses with UFW.
- Enhanced understanding of attack patterns and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

Kali Linux: A penetration testing platform used for launching simulated cyber attacks.
Wireshark: A network analysis tool for capturing and analyzing network traffic in real-time.
Metasploit: A penetration testing framework used to exploit vulnerabilities and simulate attacks.
UFW (Uncomplicated Firewall): A firewall management tool on Ubuntu for configuring and enforcing security rules.

## Steps

#### First, I updated and upgraded my Ubuntu system to ensure it is running the latest version.

<img width="1283" alt="Configuring updates on Ubuntu" src="https://github.com/user-attachments/assets/9cb5aac7-651a-4e3e-adac-9357e361aa38">

#### Next, I installed essential tools on Ubuntu, such as `gcc` and `g++`, which are necessary for compiling software.

<img width="966" alt="Installed relevant tools on Ubuntu" src="https://github.com/user-attachments/assets/3f89c8e3-019d-4e72-9e64-7da40402468b">

#### I then updated and upgraded my Kali Linux system to ensure it was running the latest version.

<img width="1275" alt="Configured updates and upgrades on Kali" src="https://github.com/user-attachments/assets/43924afd-1332-4de9-b7d0-80294aa3ad38">

#### After ensuring Kali Linux was up to date, I installed Metasploit, a tool used for simulating network attacks.

<img width="654" alt="Installed metasploit on Kali Linux" src="https://github.com/user-attachments/assets/a37f9911-3fdb-41ed-abc4-ff63df2efe02">

#### I ran a command to find the IP address of my Ubuntu machine, which I would target from my Kali machine.

<img width="742" alt="Found IP address of Ubuntu Machine" src="https://github.com/user-attachments/assets/8e6db2d5-62a8-4517-bbe3-127909350817">

#### Using the `nmap` command, I performed an advanced scan on the target IP address (192.168.64.3), which is assigned to my Ubuntu machine.

<img width="655" alt="Started simulation of attacks to Ubuntu machine from Kali Machine" src="https://github.com/user-attachments/assets/02201db3-9a7c-432c-922b-381551950308">

#### I then installed UFW (Uncomplicated Firewall) on my Ubuntu machine to protect against potential attacks.

<img width="796" alt="Installed UFW on Ubuntu Machine to defend against attacks" src="https://github.com/user-attachments/assets/6a25913c-938a-4622-b6a8-bd53fbd40428">

#### I enabled UFW to activate the firewall and ensure that it was defending against unauthorized access.

<img width="737" alt="Enabled UFW to defend against attacks" src="https://github.com/user-attachments/assets/e8af9d4d-c8bb-48da-a1b4-6053050698b0">

#### I located the IP address of my Kali machine using a command, which I needed to allow through the firewall for traffic analysis.

<img width="654" alt="Found IP address of Kali machine" src="https://github.com/user-attachments/assets/9685861a-4185-4a49-8654-7f6843d8090f">

#### I allowed network traffic from my Kali machine through UFW to enable web traffic analysis with Wireshark.

<img width="742" alt="Allowed IP address of Kali machine to bypass UFW" src="https://github.com/user-attachments/assets/1c33b847-d353-4bc0-995b-7e41e94a2b0a">

#### To confirm the configuration, I checked which IP addresses were permitted through UFW.

<img width="738" alt="Checked which IP addresses are allowed through UFW" src="https://github.com/user-attachments/assets/629e957c-df02-4813-92b8-8c0c83957016">

#### I installed Wireshark on my Ubuntu machine to analyze data packets and network traffic.

<img width="735" alt="Installed Wireshark on Ubuntu machine" src="https://github.com/user-attachments/assets/5e97a177-53f2-4881-babc-404f6a5415e7">

#### I launched Wireshark to monitor and visualize the IP addresses attempting to access my network.

<img width="738" alt="Began running Wireshark on Ubuntu machine" src="https://github.com/user-attachments/assets/2b17e513-7ee3-42f0-8017-b4f46f435eae">

#### The IP address highlighted in red corresponds to the Kali machine, indicating a successful scan and enabling me to analyze and block malicious traffic.

<img width="1328" alt="Analyzed network traffic coming from Kali machine" src="https://github.com/user-attachments/assets/2d4c2803-abb1-4135-aa50-2aac7fe0ffe4">

#### To better understand the network setup, I created a simple network diagram.

<img width="474" alt="Screenshot of network diagram" src="https://github.com/user-attachments/assets/daaa7de1-d6c0-4a7e-b9cd-129e7898f7f7">



