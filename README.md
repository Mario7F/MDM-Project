# Mobile Device Management-Project-Microsoft Intune

# ![Untitled-2024-06-22-0749](https://github.com/Mario7F/LinuxAdminProjects/assets/59115100/3d4075cb-c302-4789-96d3-a5b75a893fd6)

## This project is to display knowledge of the Microsoft Intune suite

 - Creating users and groups
 - Importing devices (Apple Mobile) and workstation (Windows Client)
 - Creating compliance policy
 - Setting up configuration profiles
 - Adding Endpoint security to provide a security baseline
 - Adding troubleshooting tips for known issues

### Tools used to accomplish the mission

  - Proxmox
  - Windows Server 2019 (Active Directory/DNS)
  - Active Directory Domain Service
  - Windows 10 Enterprise Edition
  - Entra ID Connect
  - Azure
  - Microsoft Intune
  - Powershell

### Objective - Phase 1

  - Set up on premise environment, connect a workstation to the domain and sync the environment to Azure.
  - Set up a autopilot deployment for Windows
  - Create users and assign them to a priviledge group to assist with administrative task in Intune (scope tag). Create a custom role to perform their duty (ability to set up compliance policies, device configuration and endpoint analytics).
  - Use Remote Help to assist in troubleshooting

### Objective - Phase 2

  - Set up compliance and conditional policies rules for devices.
  - Configure Apple and Android enrollments
  - Set up configuration profiles for managing device settings

### Objective - Phase 3

  - Deploy 365 on Windows and Apple device
  - Attach an app policy to the Apple device
  - Set up a deployment policy to manage software updates
  - Create endpoint security for devices for extra protection
