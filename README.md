# Learning WiFi

## Terminology and Concept

### WiFi

**Wi-Fi** or **WiFi** is a technology that allows electronic devices to connect to a wireless LAN (WLAN) network, mainly using the 2.4 gigahertz (12 cm) UHF and 5 gigahertz (6 cm) SHF ISM radio bands. A WLAN is usually password protected, but may be open, which allows any device within its range to access the resources of the WLAN network.

The Wi-Fi Alliance defines Wi-Fi as any "wireless local area network" (WLAN) product based on the Institute of Electrical and Electronics Engineers' (IEEE) 802.11 standards. However, the term "Wi-Fi" is used in general English as a synonym for "WLAN" since most modern WLANs are based on these standards. "Wi-Fi" is a trademark of the Wi-Fi Alliance. The "Wi-Fi Certified" trademark can only be used by Wi-Fi products that successfully complete Wi-Fi Alliance interoperability certification testing.

> https://en.wikipedia.org/wiki/Wi-Fi

### WLAN

A **Wireless Local Area Network (WLAN)** is a wireless computer network that links two or more devices using a wireless distribution method (often spread-spectrum or OFDM radio) within a limited area such as a home, school, computer laboratory, or office building. This gives users the ability to move around within a local coverage area and still be connected to the network, and can provide a connection to the wider Internet. Most modern WLANs are based on IEEE 802.11 standards, marketed under the Wi-Fi brand name.

> https://en.wikipedia.org/wiki/Wireless_LAN

### Station

In IEEE 802.11 (Wi-Fi) terminology, a **station (STA)** is a device that has the capability to use the 802.11 protocol.
For example, a station may be a laptop, a desktop PC, PDA, access point or Wi-Fi phone. An STA may be fixed, mobile or
portable. Generally in wireless networking terminology, a station, wireless client and node are often used
interchangeably, with no strict distinction existing between these terms. With a station also being referred as
transmitter or receiver based on its transmission characteristics.

IEEE 802.11-2007 formally defines station as:

*Any device that contains an IEEE 802.11-conformant media access control (MAC) and physical layer (PHY) interface to the wireless medium (WM).*

> https://en.wikipedia.org/wiki/Station_(networking)

### AP

In computer networking, a **Wireless Access Point (WAP)** is a networking hardware device that allows a Wi-Fi compliant
device to connect to a wired network. The WAP usually connects to a router (via a wired network) as a standalone device,
but it can also be an integral component of the router itself.

A WAP is differentiated from a hotspot, which is the physical location where Wi-Fi access to a WLAN is available.

> https://en.wikipedia.org/wiki/Wireless_access_point

### Router

A **router** is a networking device that forwards data packets between computer networks. Routers perform the "traffic directing" functions on the Internet. A data packet is typically forwarded from one router to another through the networks that constitute the internetwork until it reaches its destination node.

A router is connected to two or more data lines from different networks (as opposed to a network switch, which connects data lines from one single network). When a data packet comes in on one of the lines, the router reads the address information in the packet to determine its ultimate destination. Then, using information in its routing table or routing policy, it directs the packet to the next network on its journey. This creates an overlay internetwork.

> https://en.wikipedia.org/wiki/Router_(computing)

### Wireless Router

A **wireless router** is a device that performs the functions of a router and also includes the functions of a wireless access point. It is used to provide access to the Internet or a private computer network. It can function in a wired LAN (local area network), in a wireless-only LAN (WLAN), or in a mixed wired/wireless network, depending on the manufacturer and model.

> https://en.wikipedia.org/wiki/Wireless_router

### Hotspot

A **hotspot** is a physical location where people may obtain Internet access, typically using Wi-Fi technology, via a wireless local area network (WLAN) using a router connected to an internet service provider.

> https://en.wikipedia.org/wiki/Hotspot_(Wi-Fi)

### BSS

The **Basic Service Set (BSS)** is a set of all stations that can communicate with each other at PHY layer. Every BSS has an identification (ID) called the BSSID, which is the MAC address of the access point servicing the BSS.

The basic service set (BSS) provides the basic building-block of an 802.11 wireless LAN. In infrastructure mode, a single access point (AP) together with all associated stations (STAs) is called a BSS; not to be confused with the coverage of an access point, known as the basic service area (BSA). The access point acts as a master to control the stations within that BSS; the simplest BSS consists of one access point and one station.

### ESS

An **Extended Service Set (ESS)** is a set of two or more interconnected wireless BSSs that share the same SSID (network name), security credentials and integrated (providing translation between 802.3 and 802.11 frames) wired local area networks that appear as a single BSS to the logical link control layer at any station associated with one of those BSSs which facilitates mobile IP and fast secure roaming applications; the BSSs may work on the same channel, or work on different channels to boost aggregate throughput.

Access points in an ESS are connected by a distribution system. Each ESS has an ID called the SSID which is a 32-byte (maximum) character string.

![Wireless Lan Architecture](http://what-when-how.com/wp-content/uploads/2012/03/tmp15B103_thumb.jpg)

> http://what-when-how.com/roaming-in-wireless-networks/wlan-overview-roamingcurrent-and-future-enhancements/

### SSID

Each BSS or ESS is identified by a **service set identifier (SSID)** - a series of 0 to 32 octets. It is used as an identifier for a wireless LAN, and is intended to be unique for a particular area. Since this identifier must often be entered into devices manually by a human user, it is often a human-readable string and thus commonly called the "network name"

### IEEE 802.11

**IEEE 802.11** is a set of media access control (MAC) and physical layer (PHY) specifications for implementing wireless local area network (WLAN) computer communication in the 900 MHz and 2.4, 3.6, 5, and 60 GHz frequency bands.

> https://en.wikipedia.org/wiki/IEEE_802.11

## Infrastructure

**WLAN**

![WLAN Architecture](https://upload.wikimedia.org/wikipedia/commons/thumb/d/df/WI-FI_Range_Diagram.svg/2000px-WI-FI_Range_Diagram.svg.png)

**Wireless Router**

![Network Infrastructure](http://www.crimewatchsecurity.com/image/101183000.jpg)

**Wireless Bridge**

![Wireless Bridge](http://cdn.makeuseof.com/wp-content/uploads/2008/11/wireless-bridge-diagram.png?b34c28)

> http://www.home-network-help.com/wireless-bridge.html

**Wireless Repeater**

![Wireless Repeater](http://www.eusso.com/models/wireless/ugl2454-apa/wireless%20repeater.jpg)

## Standard Devices

### Wireless Access Point

A wireless access point (WAP) connects a group of wireless devices to an adjacent wired LAN. An access point resembles a network hub, relaying data between connected wireless devices in addition to a (usually) single connected wired device, most often an Ethernet hub or switch, allowing wireless devices to communicate with other wired devices.

### Wireless Adapter

Wireless adapters allow devices to connect to a wireless network. These adapters connect to devices using various external or internal interconnects such as PCI, miniPCI, USB, ExpressCard, Cardbus and PC Card.

### Wireless Router

Wireless routers integrate a Wireless Access Point, Ethernet switch, and internal router firmware application that provides IP routing, NAT, and DNS forwarding through an integrated WAN-interface. A wireless router allows wired and wireless Ethernet LAN devices to connect to a (usually) single WAN device such as a cable modem or a DSL modem. A wireless router allows all three devices, mainly the access point and router, to be configured through one central utility.

### Wireless Network Bridge

Wireless network bridges connect a wired network to a wireless network.

A bridge differs from an access point: an access point connects wireless devices to a wired network at the data-link layer.

Two wireless bridges may be used to connect two wired networks over a wireless link, useful in situations where a wired connection may be unavailable, such as between two separate homes or for devices which do not have wireless networking capability (but have wired networking capability), such as consumer entertainment devices; alternatively, a wireless bridge can be used to enable a device which supports a wired connection to operate at a wireless networking standard which is faster than supported by the wireless network connectivity feature (external dongle or inbuilt) supported by the device (e.g. enabling Wireless-N speeds (up to the maximum supported speed on the wired Ethernet port on both the bridge and connected devices including the wireless access point) for a device which only supports Wireless-G). A dual-band wireless bridge can also be used to enable 5 GHz wireless network operation on a device which only supports 2.4 GHz wireless networking functionality and has a wired Ethernet port.

### Wireless Repeater

Wireless range-extenders or wireless repeaters can extend the range of an existing wireless network. Strategically placed range-extenders can elongate a signal area or allow for the signal area to reach around barriers such as those pertaining in L-shaped corridors.

> https://en.wikipedia.org/wiki/Wi-Fi

## Protocol and Architecture

### General

![Network Model](http://vichargrave.com/wp-content/uploads/2013/01/Network-Stack-Models1.png)

![Network Protocols](http://heylinux.com/wp-content/uploads/2015/08/TCP-IP.gif)

> http://www.colasoft.com.cn/download/protocols_map.php

### Linux Networking Stack

![Linux Networking Stack](http://140.120.7.21/LinuxRef/IMG/ANS-figure2.gif)

> http://140.120.7.21/LinuxRef/Network/LinuxNetworkStack.html

![Networking in Linux Kernel](http://upload.wikimedia.org/wikipedia/commons/5/5b/Linux_kernel_map.png)

> http://blog.erratasec.com/2013/02/custom-stack-it-goes-to-11.html#.V5itaGXXFZ0

![Data Flow of Networking in Linux Kernel](http://image.slidesharecdn.com/linuxnetworkstack-140928020340-phpapp02/95/linux-network-stack-1-1024.jpg?cb=1411869839)

### Linux WiFi Architecture

![Realtek Linux WiFi Architecture](http://3.bp.blogspot.com/-e1LcVZ1CE0s/TxGnBSWMBXI/AAAAAAAAAGU/dalu2rx3OYw/s1600/WiFi+Direct.jpg)

> http://dishingtech.blogspot.com/2012/01/realtek-wi-fi-direct-programming-guide.html

![TI WL18xx Linux Wireless Architecture](http://processors.wiki.ti.com/images/f/fd/Wlcore.png)

> http://processors.wiki.ti.com/index.php/WL18xx_Linux_Wireless_Architecture

![Tizen Linux WiFi Architecture](https://wiki.tizen.org/w/images/thumb/1/16/Wlan.png/800px-Wlan.png)

> https://wiki.tizen.org/wiki/Porting_Guide/Connectivity

### Android WiFI Architecture

![Android WiFi Architecture](https://mitulmodi.files.wordpress.com/2012/03/android-wifi-arch-detail.jpg?w=459&h=425)

>://mitulmodi.wordpress.com/2012/03/21/android-wifi-architecture-wext/

## WiFi for IoT

### Smart-Config

TI's SimpleLink Wi-Fi CC3000 module comes with TI's unique SmartConfig technology, a one-step Wi-Fi setup process that allows multiple in-home devices to connect to Wi-Fi networks quickly and efficiently. Considering applications that typically do not have a display or keyboard to enter Wi-Fi network name and password, SmartConfig technology gives end users the ability to easily connect their CC3000-based devices to an access point. Through a simple SmartConfig technology interface, consumers can use an iOS or Android smartphone/tablet or home PC using just a simple Web browser. Software on this page gives access to the SmartConfig library and application source code in order to create your own application using TI's SmartConfig technology.

![TI CC3000 Smart-Config](http://processors.wiki.ti.com/images/2/22/Cc3000_smart_config.PNG)

> http://processors.wiki.ti.com/index.php/CC3000_Smart_Config

> http://processors.wiki.ti.com/index.php/CC3000_First_Time_Configuration

> http://electronics.stackexchange.com/questions/61704/how-does-ti-cc3000-wifi-smart-config-work

> http://depletionregion.blogspot.com/2013/10/cc3000-smart-config-transmitting-ssid.html

> http://depletionregion.blogspot.ch/2014/06/smart-config-for-consumer-products.html

> http://www.tuicool.com/articles/E3a2myi

> http://blog.csdn.net/xundh/article/details/50351888

### Configure IoT WiFi

![IoT WiFi Configuration Compare](https://media.licdn.com/mpr/mpr/shrinknp_800_800/AAEAAQAAAAAAAALYAAAAJDQ2ODJiNGM4LTAwODctNDM3ZC04MmNhLTBmOGQxMTZkN2QyNA.png)

> https://www.linkedin.com/pulse/wifi-configuration-iot-devices-dan-walkes

**Smart Config**

![Config IoT WiFi thru Smart Config](http://cdn.jxtobo.com/wp-content/uploads/2015/10/4ffce04d92a4d6cb21c1494cdfcd6dc1126.jpg)

**AP Mode**

![Config IoT WiFi thru AP](http://cdn.jxtobo.com/wp-content/uploads/2015/10/4ffce04d92a4d6cb21c1494cdfcd6dc1128.jpg)

> http://www.jxtobo.com/4572.html

## Reference
- https://en.wikipedia.org/wiki/Wi-Fi
- http://standards.ieee.org/getieee802/download/802.11-2007.pdf
- http://www.slideshare.net/hugolu/the-linux-networking-architecture
