### Learning Objectives

By the end of this chapter, you should be able to:

Manage graphical interface sessions.
Perform basic operations using the graphical interface.
Change the graphical desktop to suit your needs.

---

### Graphical Desktop

You can use either a Command Line Interface (CLI) or a Graphical User Interface (GUI) when using Linux. To work at the CLI, you have to remember which programs and commands are used to perform tasks, and how to quickly and accurately obtain more information about their use and options. On the other hand, using the GUI is often quick and easy. It allows you to interact with your system through graphical icons and screens. For repetitive tasks, the CLI is often more efficient, while the GUI is easier to navigate if you do not remember all the details or do something only rarely. 

We will learn how to manage sessions using the GUI for the three Linux distribution families that we cover the most in this course: Red Hat (CentOS, Fedora), SUSE (openSUSE), and Debian (Ubuntu, Mint). Since we are using the GNOME-based variant of openSUSE rather than the KDE-based one, all are actually quite similar. If you are using KDE (or other Linux desktops such as XFCE), your experience will vary somewhat from what is shown, but not in any intrinsically difficult way, as user interfaces have converged to certain well-known behaviors on modern operating systems. In subsequent sections of this course we will concentrate in great detail on the command line interface, which is pretty much the same on all distributions.

---

### X Window System

Generally, in a Linux desktop system, the X Window System is loaded as one of the final steps in the boot process.

A service called the display manager keeps track of the displays being provided and loads the X server (so-called, because it provides graphical services to applications, sometimes called X clients). The display manager also handles graphical logins and starts the appropriate desktop environment after a user logs in.

X Window System is a rather old system; it dates back to the mid 1980s and, as such, has certain deficiencies on modern systems (for example, with security), as it has been stretched rather far from its original purposes. A newer system, known as [Wayland](https://wayland.freedesktop.org/), is gradually superseding it and was adopted as the default display system in Fedora 25.

---

### More About X

A desktop environment consists of a session manager, which starts and maintains the components of the graphical session, and the window manager, which controls the placement and movement of windows, window title-bars, and controls.

Although these can be mixed, generally a set of utilities, session manager, and window manager are used together as a unit, and together provide a seamless desktop environment.

If the display manager is not started by default in the default runlevel, you can start X a different way, after logging on to a text-mode console, by running startx from the command line. Or, you can start the display manager (gdm, lightdm, kdm, xdm, etc.) manually from the command line. This differs from running startx as the display managers will project a sign in screen. We discuss them next.

---

### GUI Startup

When you install a desktop environment, the X display manager starts at the end of the boot process. It is responsible for starting the graphics system, logging in the user, and starting the user’s desktop environment. You can often select from a choice of desktop environments when logging in to the system.

The default display manager for GNOME is called gdm. Other popular display managers include lightdm (used on Ubuntu before version 18.04 LTS) and kdm (associated with KDE).

---

### GNOME Desktop Environment

GNOME is a popular desktop environment with an easy-to-use graphical user interface. It is bundled as the default desktop environment for most Linux distributions, including Red Hat Enterprise Linux, Fedora, CentOS, SUSE Linux Enterprise, Ubuntu and Debian. GNOME has menu-based navigation and is sometimes an easy transition to accomplish for Windows users. However, as you will see, the look and feel can be quite different across distributions, even if they are all using GNOME.

Another common desktop environment very important in the history of Linux and also widely used is KDE, which has often been used in conjunction with SUSE and openSUSE. Other alternatives for a desktop environment include Unity (from on older Ubuntu, but still based on GNOME), XFCE and LXDE. As previously mentioned, most desktop environments follow a similar structure to GNOME, and we will restrict ourselves mostly to it to keep things less complex.

---

### gnome-tweak-tool

Most settings, both personal and system-wide, are to be found by clicking in the upper right-hand corner, on either a gear or other obvious icon, depending on your Linux distribution.

However, there are many settings which many users would like to modify which are not accessible; the default settings utility is unfortunately rather limited in modern GNOME-based distributions. The desire for simplicity has actually made it difficult to adapt your system to your tastes and needs.  

Fortunately, there is a standard utility, gnome-tweak-tool, which exposes many more setting options. It also permits you to easily install extensions by external parties. Not all Linux distributions install this tool by default, but it is always available. Some recent distributions have renamed this tool as gnome-tweaks. You may have to run it by hitting Alt-F2 and then typing in the name. You may want to add it to your Favorites list as we shall discuss.

In the screenshot below, the keyboard mapping is being adjusted so the useless CapsLock key can be used as an additional Ctrl key; this saves users who use Ctrl a lot (such as emacs aficionados) from getting physically damaged by pinkie strain.

---

### Changing the Theme

The visual appearance of applications (the buttons, scroll bars, widgets, and other graphical components) are controlled by a theme. GNOME comes with a set of different themes which can change the way your applications look. 

The exact method for changing your theme may depend on your distribution. However, for all GNOME-based distributions, you can simply run gnome-tweak-tool, as shown in the screenshot from Ubuntu.

There are other options to get additional themes beyond the default selection. You can download and install themes from the [GNOME's Wiki](https://wiki.gnome.org/Personalization) website.

---

### Logging In and Out

The next few screens cover the demonstrations and Try-It-Yourself activity for members of each of the three Linux distribution families we cover in this course. You can view a demonstration for the distribution type of your choice and practice the procedure through the relevant Try-It-Yourself activity.

---

### Locking the Screen

It is often a good idea to lock your screen to prevent other people from accessing your session while you are away from your computer. Note: This does not suspend the computer; all your applications and processes continue to run while the screen is locked.

There are two ways to lock your screen:

Using the graphical interface
Clicking in the upper-right corner of the desktop, and then clicking on the lock icon.
Using the keyboard shortcut SUPER-L 
(The SUPER key is also known as the Windows key). 
The keyboard shortcut for locking the screen in the three distros can be modified by altering keyboard settings, the exact prescription varying by distribution, but not hard to ascertain.

To re-enter the desktop session you just need to provide your password again.

The screenshot below shows how to lock the screen for Ubuntu. The details vary little in modern distributions.

---

### Locking and Unlocking the Screen in More Detail

To lock and unlock your screen in openSUSE, perform the following steps:

Click the power icon on the upper-right corner of the desktop.
Click the lock icon. The screen is locked immediately.
Press Enter. The login screen is displayed.
To unlock the screen, enter the password.
Click Unlock and the desktop screen is displayed.
Note: When you lock the screen, GNOME will blank the screen or run a screensaver, depending on your settings.

---

### Switching Users

Linux is a true multi-user operating system, which allows more than one user to be simultaneously logged in. If more than one person uses the system, it is best for each person to have their own user account and password. This allows for individualized settings, home directories, and other files. Users can take turns using the machine, while keeping everyone's sessions alive, or even be logged in simultaneously through the network.

Note: The next few screens cover the demonstrations and Try-It-Yourself activity for members of each of the three Linux distribution families we cover in this course. You can view a demonstration for the distribution type of your choice and practice the procedure through the relevant Try-It-Yourself activity.

---

### Shutting Down and Restarting

Besides normal daily starting and stopping of the computer, a system restart may be required as part of certain major system updates, generally only those involving installing a new Linux kernel.

Initiating the shutdown process from the graphical desktop is rather trivial on all current Linux distributions, with very little variation. We will discuss later how to do this from the command line, using the shutdown command.

In all cases, you click on either a settings (gear) or a power icon and follow the prompts. We will only show the detail for the Ubuntu Linux distribution.

---

### Shutting Down and Restarting

Besides normal daily starting and stopping of the computer, a system restart may be required as part of certain major system updates, generally only those involving installing a new Linux kernel.

Initiating the shutdown process from the graphical desktop is rather trivial on all current Linux distributions, with very little variation. We will discuss later how to do this from the command line, using the shutdown command.

In all cases, you click on either a settings (gear) or a power icon and follow the prompts. We will only show the detail for the Ubuntu Linux distribution.

---

### Shutting Down and Restarting in Ubuntu

To shut down the computer in Ubuntu, perform the following steps:

1. On the Ubuntu desktop screen, click either the Power icon (for earlier versions) or the Gear icon in the upper-right corner of the screen.
1. Click Shut Down. The Restart and Shut Down icons are displayed.
1. Click the Shut Down icon on the right to shutdown the system and click the Restart icon on the left to restart the system.
Shutdown, reboot, and logout operations will ask for confirmation before going ahead. This is because many applications will not save their data properly when terminated this way.

Always save your documents and data before restarting, shutting down, or logging out. The Ubuntu screenshot given here is similar to all of the distribution confirmation windows.

---

### Suspending

Most modern computers support Suspend Mode or Sleep Mode when you stop using your computer for a short while. Suspend Mode saves the current system state and allows you to resume your session more quickly while remaining on, but using very little power. It works by keeping your system’s applications, desktop, and so on, in system RAM, but turning off all of the other hardware. The Suspend Mode bypasses the time for a full system start-up and continues to use minimal power.

---

### Suspending the System


To suspend the system in older Ubuntu distributions, the procedure is the same as for shutdown or locking the screen. After you click the icon in the upper right side, you just select Suspend, as shown in the below snapshot

However, it is quite simple and universal in recent GNOME-based distributions.  If you click on the Power icon and hold for a short time and release, you will get the double dot icon, which you then click to suspend the system.

Note: To wake your system and resume your session, move the mouse or press any button on the keyboard. The system will wake up with the screen locked, just as if you had manually locked it; type in your password to resume.

--- 

### Locating Applications


Unlike other operating systems, the initial install of Linux usually comes with a wide range of applications and software archives that contain thousands of programs that enable you to accomplish a wide variety of tasks with your computer. For most key tasks, a default application is usually already installed. However, you can always install more applications and try different options.

For example, Firefox is popular as the default browser in many Linux distributions, while Epiphany, Konqueror, and Chromium (the open source base for Google Chrome) are usually available for install from software repositories. Proprietary web browsers, such as Opera and Chrome, are also available.

Locating applications from the GNOME and KDE menus is easy, as they are neatly organized in functional submenus.

---

### Default Applications

Multiple applications are available to accomplish various tasks and to open a file of a given type. For example, you can click on a web address while reading an email and launch a browser such as Firefox or Chrome.

To set default applications, enter the System Settings menu (on all recent Linux distributions) and then click on Details > System > Default Applications. The exact list will vary from what is shown here in the Ubuntu screenshot according to what is actually installed and available on your system.

---

### File Manager

Each distribution implements the File Manager utility, which is used to navigate the file system. It can locate files and, when a file is clicked upon, either it will run if it is a program, or an associated application will be launched using the file as data. This behavior is completely familiar to anyone who has used other operating systems.

To start the File Manager, you will have to locate its icon, a file cabinet, which is easily found under Favorites or Applications.

The File Manager (Files in the case of Ubuntu) will open a window with your Home directory displayed. The left panel of the File Manager window holds a list of commonly used directories, such as Computer, Home, Desktop, Documents, Downloads and Trash.

You can click the Magnifying Glass icon on the top-right of the File Manager window to search for files or directories (folders).

---

### Home Directories

The File Manager lets you access different locations on your computer and the network, including the Home directory, Desktop, Computer, Network, and other attached devices. The Browse Network and Connect to Server options access networked and shared devices, such as file servers and printers present on the local network.

Every user with an account on the system will have a home directory, usually created under /home, and usually named according to the user, such as /home/student.

By default, files the user saves will be placed in a directory tree starting there. Account creation, whether during system installation or at a later time, when a new user is added, also induces default directories to be created under the user's home directory, such as Documents, Desktop, and Downloads.

In the screenshot shown for CentOS 7, we have chosen the list format and are also showing hidden files (those starting with a period). See if you can do the same on your distribution.

---

### Viewing Files

The File Manager allows you to view files and directories in more than one way.

You can switch between the Icons and List formats, either by clicking the familiar icons in the top bar, or you can press CTRL-1 or CTRL-2 respectively.

In addition, you can also arrange the files and directories by name, size, type, or modification date for further sorting. To do so, click View and select Arrange Items.

Another useful option is to show hidden files (sometimes imprecisely called system files), which are usually configuration files that are hidden by default and whose name starts with a dot. To show hidden files, select Show Hidden Files from the menu or press CTRL-H.

The file browser provides multiple ways to customize your window view to facilitate easy drag and drop file operations. You can also alter the size of the icons by selecting Zoom In and Zoom Out under the View menu.

The screenshot is taken from openSUSE.

