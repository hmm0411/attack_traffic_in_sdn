# SDN Traffic Dataset (.pcap)

This repository contains both **normal** and **attack** traffic captures simulated in a **Software-Defined Networking (SDN)** environment using **Mininet**. The dataset is intended for use in:
- Intrusion Detection Systems (IDS)
- Traffic Classification
- SDN Security Research

---

## PCAP Files

| File Name                    | Description                                  | Download Link |
|-----------------------------|----------------------------------------------|----------------|
| `normal.pcap`               | Normal traffic: web browsing, video streaming, etc. | [Download (Google Drive)](https://drive.google.com/file/d/1RlMUb3NPaMyDhshiG7aGeNLhHs_FDqfr/view?usp=sharing)|
| `dos.pcap`                  | Basic Denial-of-Service attack               | [View on GitHub](https://github.com/hmm0411/attack_traffic_in_sdn/blob/main/dos.pcap) |
| `ddos.pcap`                 | Distributed DoS attack from multiple hosts   | [Download (Google Drive)](https://drive.google.com/file/d/13cbx6zRTIX23h4IxdPJ4VqygsTX_IVJK/view?usp=sharing) |
| `replay_attack.pcap`        | Replay of previously captured malicious flows | [Download (Google Drive)](https://drive.google.com/file/d/1wba_uCGm5qPJz_s6RX1AmNhUOJLVAvR-/view?usp=sharing) |
| `flow_table_exhaustion.pcap`| Flooding flow table entries in SDN switches  | [View on GitHub](https://github.com/hmm0411/attack_traffic_in_sdn/blob/main/flow_table_exhaustion.pcap) |
| `mitm.pcap`                 | ARP spoofing / Man-in-the-Middle attack in SDN | [View on GitHub](https://github.com/hmm0411/attack_traffic_in_sdn/blob/main/mitm.pcap) |

---

## Dataset Details

- **Environment:** Mininet (with SDN controller Ryu)
- **Capture Tools:** `Scapy`, `Hping3`, `Tshark`, `tcpdump`
- **Attack Scripts:** Python scripts using Scapy + hping3 CLI
- **Format:** `.pcap` files (analyzable with Wireshark / Tshark)
- **Use Cases:**
  - Machine Learning / Deep Learning model training
  - Flow feature extraction and classification
  - Research on Flow Table Exhaustion, Replay, MITM in SDN

---

## Contact

For questions or requests (e.g., labeled `.csv`, preprocessing scripts), feel free to contact:

- Email: [23520964@gm.uit.edu.vn](mailto:23520964@gm.uit.edu.vn)

---
