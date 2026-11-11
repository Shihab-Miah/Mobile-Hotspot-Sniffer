# Mobile-Hotspot-Sniffer (PacketShark)

> **Real-Time Wireshark-Grade Packet Sniffer, Live Terminal Streamer & Hotspot Traffic Analyzer for Android Dolphy.**

## Overview

**PacketShark** is an advanced network diagnostic and packet capture plugin built for the **Dolphy** Android platform. It inspects local interface traffic and connected hotspot devices (such as laptops connected to your mobile hotspot) in real-time with full protocol dissection and live terminal streaming.

## Features

- **Live Stream Console**: Continuous Linux-style terminal streaming (`tcpdump` / `tshark` format) with live throughput and packet counters.
- **Protocol Dissection**: Decodes Ethernet II, IPv4, IPv6, ARP, TCP, UDP, ICMP, DNS (queries & answers), HTTP, TLS SNI (handshake domain inspection).
- **Hotspot Device Tracking**: Automatically detects hotspot clients (e.g., connected laptop) and isolates per-client bandwidth, IP, MAC, and accessed domains.
- **Direct PCAP Export & Import**: Save captures directly to standard `.pcap` files compatible with desktop Wireshark.
- **Native Dolphy Jetpack Compose UI**: Fast throttled UI updates for responsive live streaming.

## Installation in Dolphy

1. Copy `PacketShark.dolphyplugin` to `/sdcard/Download/Dolphy/`.
2. Open **Dolphy**.
3. Under the **PLUGINS** section on the Home screen, tap **PacketShark**.
4. Tap **▶ Start Live Stream** to monitor traffic.

## License
MIT
