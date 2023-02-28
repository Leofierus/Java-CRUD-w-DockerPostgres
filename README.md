# Java-CRUD-w-DockerPostgres

## Tools needed to be installed

### Prerequisites
- Windows 10

### Docker setup

1. Download `Docker-setup` using the [Docker download page](https://docs.docker.com/get-docker/) for your respective Operating System. (**Note**: The following installation steps were performed on a Windows OS).

2. Make sure you have Hyper-V enabled on your computer. To check, run the following command on your command prompt:
   ```bash
   > systeminfo
   ```
   **Expected Output** (At the end of the output, you should see the following line):
   ```bash
   Hyper-V Requirements: A hypervisor has been detected. Features required for Hyper-V will not be displayed.
   ```

3. Click on the `.exe` that you just downloaded and follow the installation process.

4. Once your computer has been restarted, along with Docker, you may be faced with the following prompt

      ![](https://cdn.discordapp.com/attachments/979322168720621608/979326879146344478/WSL2_prompt.png)
   
   To Proceed, just click on the link and follow the procedures to install `WSL2 Linux kernel` for Windows. 

5. If you see the following screen after opening Docker, then you have successfully installed Docker on your machine.

      ![](https://cdn.discordapp.com/attachments/979322168720621608/979328007212773386/Docker_Homepage.png)
      
6. To verify that Docker Desktop is installed correctly and running, you can open a command prompt and run the following command:
   ```bash
   > docker --version
   ```
   This command should display information about the installed version of Docker.
   
### Installing Java 17

#### Step 1: Download Java 17
  - Go to the [Java SE Development Kit 17](https://www.oracle.com/java/technologies/downloads/#jdk17-windows) Downloads page.
  - Click the "Download" button for the "Windows x64 Installer" package.
  - Accept the license agreement and download the file.
  
#### Step 2: Install Java 17
  - Double-click the downloaded file to start the installation process.
  - Follow the prompts in the installer, and choose a location for the installation.
  - Click "Next" and then "Close" when the installation is complete.
  
#### Step 3: Configure the system path
  - Right-click on the "Start" button and select "System".
  - Click on "Advanced system settings" on the left-hand side.
  - Click on the "Environment Variables" button.
  - Under "System Variables", scroll down and select the "Path" variable, then click "Edit".
  - Click "New" and enter the path to the "bin" directory of the Java installation, for example:
  
    ```bash
    C:\Program Files\Java\jdk-17\bin
    ```
  - Click "OK" to close all windows.
  
#### Step 4: Verify the installation
  - Open a command prompt and type the following command:
  
    ```bash
    java --version
    ```
  - Verify that the output shows "Java version 17.x.x".
  
### Installing IntelliJ Community Edition

1. Go to the [IntelliJ IDEA download page](https://www.jetbrains.com/idea/download/) and download the Community edition for your operating system.

2. Once the download is complete, run the installation file.

3. Follow the prompts in the installer, and choose a location for the installation.
