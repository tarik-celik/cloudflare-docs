---
weight: 8
pcx_content_type: how-to
title: Linux
meta:
    title: Set up 1.1.1.1 on Linux
---

# Set up 1.1.1.1 - Linux

Take note of any DNS addresses you might have set up, and save them in a safe place in case you need to use them later.
## With commandline 

1. > $ sudo nano /etc/systemd/resolved.conf
2. Uncomment the DNS line
3. to use 1.1.1.1 resolver: write 1.1.1.1 or 1.0.0.1 after
"DNS=", like "DNS=1.1.1.1" 
For blocking malware use 1.1.1.2 or
1.0.0.2
For blocking malware and adult
content use; 1.1.1.3 or 1.0.0.3
## With Gui
## GNOME

1. Go to **Show Applications** > **Settings** > **Network**.
2. Select the adapter you want to configure — like your Ethernet adapter or Wi-Fi card — and select the **Settings** button.
3. On the **IPv4** tab > **DNS** section, disable the **Automatic** toggle.
4. {{<render file="_all-ipv4.md">}}
5. Go to **IPv6**.
6. {{<render file="_all-ipv6.md">}}
7. Select **Apply**.
  
## KDE Plasma
  
1. Go to **System Settings** > **Connections**.
2. Select the connection you want to configure - like your current connected network.
3. On the **IPv4** tab, select the **Method** drop-down menu > _Automatic (Only addresses)_.
4. Select the text box next to **DNS servers**.
5. {{<render file="_all-ipv4.md">}}
6. On the the **IPv6** tab, select the **Method** drop-down menu > _Automatic (Only addresses)_.
7. Select the text box next to **DNS servers**.
8. {{<render file="_all-ipv6.md">}}
9. Select **Apply**.

{{<render file="_captive-portals.md">}}
