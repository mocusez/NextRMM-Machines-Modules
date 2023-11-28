# Machine Module

The project uses NextJS

Default front-end libraries are Shadcn, Tanstack/query, Tanstack/Table, Recharts.

If you need to add new dependent libraries (e.g. charts), you need to let us know and discuss them in advance.

This section should support both mobile and computer displays.

## Details Page

Mainly reference NinjaRMM

https://www.youtube.com/watch?v=TzhemHxauLQ

### Information to be displayed

In addition to the basic information available on the home page, more detailed information needs to be displayed (**The following information is retrieved by the Agent or database**):

For example, the overview of the machine

Windows:

Windows systems should also show serial numbers

![ninja-windows](readme.assets/ninja-windows.png)

Linux:

![ninja-linux](readme.assets/ninja-linux.png)

File information

![ninja-linux-file](readme.assets/ninja-linux-file.png)

Firewall status, AntiVirus status, network IP (intranet and extranet), open ports, system logs

![ninja-linux-activity-log](readme.assets/ninja-linux-activity-log.png)

Device details (device name, memory capacity, CPU, CPU hardware information).

![ninja-windows-detail](readme.assets/ninja-windows-detail.png)

Show warnings by time, scripts running (Activity Log)

If the device has a GUI, it needs to be able to display the current device screen.

Note information about the device

![ninja-create-log](readme.assets/ninja-create-log.png)

### Required Configuration

Buttons/interfaces for remote desktop (AnyDesk, Teamviewer, RustDesk) access.

![ninja-remote-control](readme.assets/ninja-remote-control.png)

Window to display device's hard disk usage, software installations (management of sources such as apt, winget), processes running.

Software

![ninja-windows-software](readme.assets/ninja-windows-software.png)

Process control

![ninja-windows-process-control](readme.assets/ninja-windows-process-control.png)

Windows needs to be able to display service registrations and patch installations.

![ninja-windows-OSpatch](readme.assets/ninja-windows-OSpatch.png)

Enable CLI for the current terminal through a window