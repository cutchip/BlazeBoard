# BlazeBoard - Digital Signage Kiosk Solution

![BlazeBoard Icon](logo.png)

Transform any Windows PC into a powerful, multi-screen digital signage solution with BlazeBoard. Designed for simplicity and scalability, BlazeBoard turns your displays into dynamic information hubs, perfect for corporate lobbies, retail spaces, manufacturing floors, and educational institutions.

BlazeBoard is a lightweight, full-screen kiosk application that automatically detects every monitor connected to a device and gives each one a unique purpose. Centrally manage your entire fleet of displays using standard Windows tools, eliminating the need for expensive, proprietary signage software.

### Key Features
* **Multi-Monitor Support:** Automatically detects all connected displays and creates a dedicated kiosk window for each.
* **Flexible Layouts:** Choose per-screen layouts:
    * **Static:** Display a single, refreshing webpage.
    * **Slideshow:** Rotate through a list of webpages at a set interval.
    * **2x2 Grid:** Show four webpages in a 2x2 grid.
* **Centralized Management:** Fully configurable via Windows Registry or Group Policy (ADMX/ADML templates provided).
* **High-Resolution Ready:** Configurable zoom factor ensures content looks great on any display, from 1080p to 4K.
* **Kiosk-Ready:** Designed for Windows Assigned Access (Kiosk Mode) and standard desktop use.

### Installation (for End Users)

1.  Go to the **[Releases page](httpss://github.com/YourUsername/BlazeBoard/releases)**.
2.  Download the latest `BlazeBoard.msi` installer and the `setup.exe` bootstrapper.
3.  Run `setup.exe` to install the application and any prerequisites (like the WebView2 Runtime).

### Configuration (for Administrators)

BlazeBoard is configured via the Windows Registry under `HKEY_LOCAL_MACHINE\SOFTWARE\BlazeBoard`.

For easy deployment, we strongly recommend using the provided Group Policy templates.

1.  Download the `BlazeBoard.admx` and `Blazeboard.adml` files from the latest **[Release](httpss://github.com/YourUsername/BlazeBoard/releases)**.
2.  Copy them to your domain controller's PolicyDefinitions folder (e.g., `C:\Windows\PolicyDefinitions` and `C:\Windows\PolicyDefinitions\en-US`).
3.  Open the Group Policy Management Console and navigate to **Computer Configuration > Policies > Administrative Templates > BlazeBoard**.
4.  Configure the settings for each screen as needed.


