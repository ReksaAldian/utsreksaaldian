# UTS Sistem Administrasi Server
------
## Reksa Aldian Rahmandy Putra(1202192048)/IT 02-01
------
**Question**
------
<img width="461" alt="bbbb" src="https://user-images.githubusercontent.com/92350603/143621126-49a7a818-0d3d-4a3f-b737-ff4fafdae37f.PNG">

**Answer**
------
### A. Instalasi windows server 2022

Download ISO Installer windows server 2022

   https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
   
   Select download the `ISO` then follow it step by step.
   
   <img width="874" alt="cccc" src="https://user-images.githubusercontent.com/92350603/143621513-6da949ad-311d-4c4b-af20-f8dc3031a9e4.PNG">

- Then open `Oracle VM`

![OPEN VB](https://user-images.githubusercontent.com/95138486/143688065-ece9dd66-309b-4f96-be26-922abba558c4.png)
  
- Next Klik `New`, and do it like the picture below :
  
  Enter the name of the machine and type of system to use
  
  ![2](https://user-images.githubusercontent.com/95138486/143688435-7c7ef7c6-2c09-4bba-8c60-44b0e1844105.png)


- Define ram, create the disk defining type and size

![3](https://user-images.githubusercontent.com/95138486/143688457-d0e746d6-90c2-443c-8685-720ec0359f4b.png)

![4](https://user-images.githubusercontent.com/95138486/143690117-1d37dd73-c0ce-4cc0-995a-a6c8d79439c4.png)

![VDI](https://user-images.githubusercontent.com/95138486/143690173-1bcef34f-50b8-4a86-a54d-cc826b2f3b54.png)

![VDI 50GB](https://user-images.githubusercontent.com/95138486/143690182-4b5c9041-a671-46f6-83c1-ccc4967a263e.png)

-  Click on `Start` and select the `ISO downloaded`

![MASUKAN ISO](https://user-images.githubusercontent.com/95138486/143690294-b730e50e-803a-4305-936a-0a8b46955e7e.png)

-  Click on `Start` and the Windows Server 2022 installation wizard will load

![MASUK MICROSOFT](https://user-images.githubusercontent.com/95138486/143690374-e4786ed4-de74-4664-9fd2-b8697832ae42.png)

-  Click on `Install now`

![INSTALL](https://user-images.githubusercontent.com/95138486/143690416-7f61be48-8e57-47e9-898f-1b0c0bcf98cf.png)

- Select windows server 2022 desktop experience

![OPERATING SYSTEM](https://user-images.githubusercontent.com/95138486/143690446-be6428e6-7d9e-40a3-878a-6978ce62f190.png)

- Accept the license and then proceed with the installation of Windows Server 2022

![LISESNI](https://user-images.githubusercontent.com/95138486/143690463-ad853c4d-c686-4331-8ca6-1fe3f3640a29.png)

- Select windows server 2022 install microsoft server advanced (Custom)

![TYPE INSTALLATION](https://user-images.githubusercontent.com/95138486/143690502-0e013084-1842-418d-b585-afb601c364e2.png)

- Location installation of windows server 2022

![PARTISI](https://user-images.githubusercontent.com/95138486/143690514-e54f7250-05c9-4d13-a282-7c61a5433084.png)

- installation progress

![PROSES INSTALASI](https://user-images.githubusercontent.com/95138486/143690528-3bd9c79e-de60-4192-ae9c-9be675a47549.png)

- The system will reboot to complete the process

![BOOTING WINDOWS](https://user-images.githubusercontent.com/95138486/143690553-8e32d25d-b328-4463-8b08-22d3e565cab5.png)

- Access the menu `Input ??? Keyboard ??? Insert Ctrl + Alt + Del`. Enter the password created and wait for the configuration to load

![TAMPILAN AWAL](https://user-images.githubusercontent.com/95138486/143690631-d3112114-e833-44e9-a230-95775856c963.png)

- Windows Server 2022 has been successfully installed

![TAMPILAN AWAL WINDOWS](https://user-images.githubusercontent.com/95138486/143690567-555736e7-577e-4c95-af00-55aa65f9e470.png)

![WINDOWS SERVER SPECIFIATION](https://user-images.githubusercontent.com/95138486/143690699-d5ca2f1c-1612-49f5-849d-7c2fe2943a3a.png)


### B. Instalasi Active Directory Domain Services
-  Before doing the installation, we change the computer name first by going to windows powershell.
   Then type `rename-computer -Newname Server2022`
      - Open the start menu and select `Windows PowerShell`
![OPEN MENU START AND SELECT](https://user-images.githubusercontent.com/95138486/143690779-0757bcbd-9cb1-4c96-8c15-35bb56a35f49.png)
   
   ![WINDOWS POWERSHELL](https://user-images.githubusercontent.com/95138486/143690811-44479ceb-ea37-4faa-8b96-598d3c962978.png)
   
      - Then Restart, and open`Server Manager` 
      
      ![SERVER MANAGER](https://user-images.githubusercontent.com/95138486/143690840-9cc6a54e-72cc-4689-a54b-436198ac8545.png)
   
      - Select Menu `manage`, Then `Add Rules and Features` 
      
      ![SELECT MENU MANAGE](https://user-images.githubusercontent.com/95138486/143690881-5a836408-0b9e-48d1-9243-b780d61eb614.png)
   
      - Select Next
      
      ![SELECT NEXT SETELAH MENU MANAGE](https://user-images.githubusercontent.com/95138486/143725766-f603bbd1-b184-4fc5-af16-e096b4e92b98.png)
   
      - Select option`Role-based or feature-based installation`. And `Next`
      
      ![SELECT OPTION ROLE BASED](https://user-images.githubusercontent.com/95138486/143725782-82651090-739e-4950-81ce-005f90953210.png)
  
      - Click `Select a server from the server pool` to select a local storage directory. Then `Next`
      
      ![SERVER POOL](https://user-images.githubusercontent.com/95138486/143725792-25613d79-e575-43e1-80ad-be5c30a6ac2b.png)
   
      - Next, put a check mark in the `Active Directory Domain Services` box. When you check the box, on the right appears 
        a brief description of ADDS and how it works. Then click `Add Features`.
   
      ![ACTIVE DIRECTORY DOMAIN SERVICES](https://user-images.githubusercontent.com/95138486/143725813-6e28ffd1-a4f3-47da-8432-7d145630ec9b.png)
   
### C. Instalasi DNS server
   - We need to install and configure the Active Directory role and DNS server to work together.
     Checklist `DNS Servers` then `add features` 
   
   ![INSTALLASI DNS SERVER](https://user-images.githubusercontent.com/95138486/143725839-a077ec41-b770-4fe5-b305-a7304bb40b4b.png)
   
   ![INSTALLASI DNS SERVER NEXT](https://user-images.githubusercontent.com/95138486/143725833-d524cfc0-7c00-4394-90f5-a9cb28126eac.png)
   
   

### D. Instalasi Net Framework 3.5
   - Checklist `.NET Framework 3.5 features`
   
   ![INSTALLASI NETFRAMWORK](https://user-images.githubusercontent.com/95138486/143725849-841b8bbf-9910-4013-a91e-11be14ee4c3c.png)
  
   - Click `Next`

    
   ![NEXT NETFRAMEWORK](https://user-images.githubusercontent.com/95138486/143725929-5db8a369-e8ab-435a-a2e3-f6d744284c9f.png)

  
   - Click `Next`again
   
   ![NEXT FRAMEWORK AGAIN](https://user-images.githubusercontent.com/95138486/143725932-b2e040ee-7d82-4c0c-b709-1576b1ec17e2.png)
   
   - Select `Install`

   ![INSTALLASI PROGRES FRAMEWORK](https://user-images.githubusercontent.com/95138486/143725982-cc1820a9-054d-49e5-8d32-45c2c860f4a0.png)
 
   - And Success `Yeahhh`

   
   ![HASIL INSTALLASI NETFRAME](https://user-images.githubusercontent.com/95138486/143725943-01511bdc-460c-4711-b5cd-94ecb0012ab1.png)
 

### E. Promote Server to a Domain Controller
-  Setting to static ip using `cmd`, type `sconfig`
  
   
   
-  Setting the IP Address Server-ADDS and pointing the DNS to the static IP address used.
   
   
-  Click `Promote this server to a domain controller` for ADD configuration
   
-  Select `Add a new forest` and enter the domain name to be used in the Root Domain Name. For example here I use the domain `fairuz.com`

  

-  Select `Windows Server 2016` at the functional level, put a check mark on `Domain Name System (DNS) server` and `Global Catalog (GC)`. 
   And fill in the Directory Services Restore Mode password with strong password criteria.
   

-  then click `Next`

   
-  Fill in `The NetBIOS domain name` according to the domain name used.
   

-  Skip the Paths section, click `Next`.

   
-  Check the configuration specified in `Review Options`, if it is TRUE. Click `Next`.
  

-  If there is `All prerequisite checks passed successfully.` Click `Install` to apply the specified configuration.
   

-  After the installation is complete, the laptop will restart automatically. Then login using administrator password
   

-  To check the configuration results, open cmd and type `netdom query fsmo`
  



