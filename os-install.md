# :pushpin: Installing a new Operating System - Why?
The pre-installed Windows 10 Pro on this machine has caused significant performance issues. The hardware struggles to meet the OS's high demands, resulting in constant slowdowns, frequent freezes, and occasional unexpected shutdowns. **Even basic tasks, like web browsing with Vivaldi** (lightweight browser)**, are frustratingly slow**. Recognizing that the machine was unable to handle the demands of this OS effectively, I decided to switch to a lighter operating system that would be more compatible with my hardware. This change was made in hopes of achieving better performance and managing temperatures more effectively.

## :mag: Choosing the new OS.
This proved to be quite a task. I began by researching online and asking in forums about other users' experiences with this specific type of device. I wanted to know if anyone had tested different operating systems on it and whether they encountered any compatibility issues. To be brutally honest, aside from one user who confirmed success with Linux Mint, I received little to no feedback. It seemed either no one had tried this before, or they simply didn't care enough to respond.

With limited guidance, aside from a good friend of mine, I started searching for lightweight operating systems on my own **and decided to test compatibility issues later on**. Among the candidates, I identified several Linux distributions that seem to work quite well for low-spec and older hardware.

- Lubuntu - https://lubuntu.me/
- Puppy Linux - https://puppylinux-woof-ce.github.io/
- Antix - https://antixlinux.com/
- MiniOS - https://minios.dev/es/
- Linux Mint - https://linuxmint.com/
- Bodhi - https://www.bodhilinux.com/
- TinyCore - http://tinycorelinux.net/
- Android 5.1 - https://en.wikipedia.org/wiki/Android_Lollipop

Many of these distributions are lightweight and, when paired with the right desktop environment, are perfect for low-spec devices like mine. They can give new life to old hardware.

## :wrench: Tools used for the installation.
I used Ventoy to make installing the new OS easier. It allowed me to _drag and drop_ multiple ISO files on one USB drive, so I could test and install different operating systems without having to make a new bootable USB every time. This software has been incredibly handy for managing the installation process.
[Ventoy site](https://www.ventoy.net/en/index.html).

## :floppy_disk: Installing the new OS.
This task turned out to be more tedious than I expected. I ran into compatibility issues with most of the distros, particularly with the eMMC storage and the Wi-Fi and Bluetooth card. Antix and Lubuntu seemed to be the best options, while MiniOS, Bodhi, and PuppyOS and pretty much all the others, constantly struggled during installation, as they couldn't recognize the eMMC storage as a valid install destination.

### :clipboard: Here are the results of my testing
<table>
    <tr>
        <th>Operating System</th>
        <th>eMMC compatible</th>
        <th>Wifi card compatible</th>
    </tr>
    <tr>
        <td>Lubuntu</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Puippy Linux</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>AntiX</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>MiniOS</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Linux Mint</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Bodhi</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>TinyCore</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Android 5.1</td>
        <td></td>
        <td></td>
    </tr>
</table>
