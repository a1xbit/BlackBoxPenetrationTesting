<h1>Black Box Penetration Testing</h1>

<h2>Description</h2>
This project demostrates Black Box Penetration Testing which does not have any previous knowledge of the layout or machines. It is conducted within an isolated virtual environment that is not connected to the internet. The exploit that will be used on this machine is CVE-2017-0143 or eternalBlue which is a Microsoft Windows Server Message Block (SMBv1) Remote Code Execution Vulnerability. <br />


<h2>Environments Used </h2>

- <b>Kali Linux</b>
- <b>Windows Server 2008 R2</b>

<h2>Discovering Kali Machine via Ifconfig </h2>

![ifconfig of kali_machine](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/f720a82b-377a-4c23-9acb-575acfa4e84c)

<h2>Discovering Windows Machine IP Address via Nmap </h2>

![arp   nmap-scan of 192 168 0 0:24](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/92a8081d-1b90-4b21-8790-1d0285a691fa)

<h2>Discovering Windows Machine Vulnerability via Nmap </h2>

![nmap -Pn -sV -F ip --script vuln](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/79cdf8e9-4f27-4b27-aa88-e614ec74a294)

<h2>Configure Exploit Options via Metasploit </h2>

![win_eternalBlue_exploit_1](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/0f1c2553-d383-4702-974c-c23f539d5d00)

![win_eternalBlue_exploit_2](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/87b919ed-65f9-482e-9547-f8314a5d9b28)

<h2>Exploit Vulnerability via Metasploit </h2>

![win_eternalBlue_exploit_3](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/bbf97719-4822-49f2-9818-02588bd97e6b)

![win_eternalBlue_exploit_4](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/91cc7aa0-0f5f-49e0-b8b3-f1ed3d84b683)

<h2>Use Meterpreter to Print Working Directory </h2>

![win_eternalBlue_exploit_5](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/8a72e631-f0a5-4c6f-81e8-ef858fec0fbd)

<h2>Use Meterpreter to Hashdump hashes of Accounts</h2>

![win_eternalBlue_exploit_6](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/229cc586-6f85-4e20-8cbe-c062541a8009)

<h2>Use Meterpreter to Confirm Windows Machine IP Address via Shell </h2>

![win_eternalBlue_exploit_7](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/374c18bd-1a97-48c6-bf26-354d586c5667)

<h2>Use Meterpreter to list all Net Users </h2>

![win_eternalBlue_exploit_8](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/8f8da765-2dc5-4037-be51-125846111485)

<h2>Use Meterpreter to Confirm Windows Administrative Privilege via Getuid </h2>

![win_eternalBlue_exploit_9](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/b2865dd6-fa1c-477d-887d-55fa75d926da)

<h2>Use Meterpreter to Add a Net LocalGroup Administrator via Shell </h2>

![net localgroup Admin HackedbyJedi :add](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/769d2b03-18b3-4c1b-8d60-5c4094aa6c7a)

<h2>Use Meterpreter to Add a Net LocalGroup Administrator Password via Shell </h2>

![net user HackedbyJedi  PW  :add](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/e996f5af-1189-4e14-beca-bda576e3be1e)

<h2>Windows Login Screen with new Administrator Account </h2>

![Windows Server 2008 R2 HackebyJedi](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/c7b1f1a7-1da1-451e-b7ee-2aad482e4794)

<h2>Inside Windows Machine with new Administrator Account </h2>

![Admin Privilieges HackedbyJedi](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/5bd4fb66-9717-434f-ae2f-6e9232745357)

<h2>Confirmation of Windows IP Address via Powershell </h2>

![win-server powershell ](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/43260c62-db7a-48a4-a769-a7368509d1e4)

<h2>Changed previous Administrator Password via Control Panel </h2>

![One could change Admin Password](https://github.com/a1xbit/BlackBoxPenetrationTesting/assets/119477838/5d6153be-590b-4942-b4bd-44bb6f71d603)
