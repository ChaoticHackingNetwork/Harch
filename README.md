# Harch {Hackers Arch} - A quick(depending on Internet Speed), simplistic Arch box with a small portion of powerful hacking tools, a badass lightwieght hacker OS!

Updates 10/27/2020:

~~Fix BIOS/UEFI bug~~.....
UEFI grub-install is taking longer than usual, working on solution 


Harch = A 'really' basic script install for Arch Linux BIOS/UEFI systems
  To install, boot into Arch live ISO and:
  
  
    1. curl -O https://raw.githubusercontent.com/ChaoticHackingNetwork/Harch/main/Harch
    2. chmod +x Harch
    3. ./Harch
    * Some systems show a bad meterpreter if so run: sed -i -e 's/\r$//' Harch 
    4. After Harch install, it will download HarchPOST
    5. arch-chroot /mnt
    6. chmod +x HarchPOST
    7. ./HarchPOST

Tools will be broken down into categories for a more user preferred system, not every tool is needed

    1. Web-Tools = Web App and Wireless Tools, i.e. Metasploit, Dirbuster etc...
    2. Cracking-Tools = PW Cracking tools , i.e Hydra, Hashcat etc...
    3. Forensic-Tools = Tools for Forensics, i.e. Maltego, Steghide etc...
    
    
  
