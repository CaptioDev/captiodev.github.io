---
title: "Raspberry Pi 4 vs. Raspberry Pi 5: A Nice Little Comparison"
date: 2024-09-16 18:39:00 -0400
categories: [Technology, Raspberry Pi]
tags: [Raspberry Pi, SBC, Comparison]
image:
  path: /assets/img/rpi5.jpg
  alt: "Raspberry Pi 4 vs. Raspberry Pi 5"
toc: true
---

The Raspberry Pi series is well-known for providing affordable, versatile, and powerful single-board computers. Here, I am going to discuss the changes and advantages of the RPi 5 over the RPi 4.

## Introduction
The Raspberry Pi 4 which was released in 2019, is a popular choice for hobbyists, educators, and professionals (Mostly hobbyists, I've never honestly seen an educator using Raspberry Pi... Sadly.). Now with the **Raspberry Pi 5**, we have a more powerful successor!

### Key Specifications

| Specification              | Raspberry Pi 4                   | Raspberry Pi 5                  |
|----------------------------|----------------------------------|---------------------------------|
| **Processor**              | 1.5 GHz quad-core Cortex-A72     | 2.4 GHz quad-core Cortex-A76    |
| **RAM Options**            | 2GB, 4GB, 8GB                    | 4GB, 8GB, 16GB                  |
| **GPU**                    | VideoCore VI                     | VideoCore VII                   |
| **USB Ports**              | 2x USB 3.0, 2x USB 2.0           | 2x USB 3.0, 2x USB 2.0          |
| **Networking**             | Gigabit Ethernet, Wi-Fi 5        | 2.5G Ethernet, Wi-Fi 6          |
| **Power Supply**           | USB-C (5V, 3A)                   | USB-C (5V, 5A)                  |

## Processor Performance

The Raspberry Pi 5 comes with a more powerful **2.4 GHz quad-core Cortex-A76** CPU compared to the Raspberry Pi 4’s **1.5 GHz quad-core Cortex-A72**. This improvement significantly boosts processing power, making the Raspberry Pi 5 faster and more efficient for demanding tasks like **media processing** or **machine learning** applications (Yay PyTorch!)

## RAM and Storage Options

The Raspberry Pi 5 has new **RAM configurations** up to 16GB, compared to the maximum 8GB available on the Pi 4. So the Raspberry Pi 5 is better for more memory-intensive tasks such as running **virtual machines** or working with **large datasets**. You can also use the Pi 5 for applications like Kasm, if you need some nice virtualization.

## Connectivity and Networking

Networking is another area where the Raspberry Pi 5 has a clear advantage. The inclusion of **Wi-Fi 6** and **2.5G Ethernet** ensures faster and more reliable connectivity, making it the better choice for **networking projects** or **IoT applications**.

## GPU and Media Capabilities

The Raspberry Pi 4 comes with a **VideoCore VI** GPU, the Pi 5 has a **VideoCore VII** GPU. This upgrade has better **4K video playback** and **gaming performance**, making the Pi 5 more suited for **media centers** or **graphics-intensive projects**. Although I don't think gaming should be the main task of any Raspberry Pi.

## Power Supply and Efficiency

With a higher-performing processor and additional features, the Raspberry Pi 5 requires a more powerful **USB-C (5V, 5A)** power supply, whereas the Raspberry Pi 4 operates on a **USB-C (5V, 3A)** power supply. If you're upgrading from the Pi 4, you’ll need to make sure your power supply can supply enough power, or else you will under-volt your Raspberry Pi! (Please make sure...)

## Conclusion

The **Raspberry Pi 5** is a pretty big step up from the **Raspberry Pi 4**, with significant improvements in processing power, memory options, and connectivity. For more complex projects, intense networking, VPNs, and Docker stuffs, the Raspberry Pi 5 is a much much better choice. However, for more basic projects or budget users, the **Raspberry Pi 4** is still an honestly great computer.
