# SDN Attack Traffic Dataset (.pcap)

This repository contains traffic captures of various network attacks simulated in a **Software-Defined Network (SDN)** environment. The dataset is intended for use in **intrusion detection**, **traffic classification**, and **SDN security research**.

---

## PCAP Files

| File Name                    | Description                                  | Download Link |
|------------------------------|----------------------------------------------|----------------|
| `dos.pcap`                   | Basic Denial-of-Service attack               | [View on GitHub](https://github.com/hmm0411/attack_traffic_in_sdn/blob/main/dos.pcap) |
| `ddos.pcap`                  | Large-scale Distributed DoS attack           | [Download (Google Drive)](https://drive.google.com/file/d/13cbx6zRTIX23h4IxdPJ4VqygsTX_IVJK/view?usp=sharing) |
| `replay_attack.pcap`         | Replay of previously captured malicious flow | [Download (Google Drive)](https://drive.google.com/file/d/1wba_uCGm5qPJz_s6RX1AmNhUOJLVAvR-/view?usp=sharing) |
| `flow_table_exhaustion.pcap` | Attack flooding flow table in SDN switch     | [View on GitHub](https://github.com/hmm0411/attack_traffic_in_sdn/blob/main/flow_table_exhaustion.pcap) |
| `mitm.pcap`                  | ARP spoofing / MITM capture in SDN           | [View on GitHub](https://github.com/hmm0411/attack_traffic_in_sdn/blob/main/mitm.pcap) |

---

## Dataset Details

- **Capture Tool:** Scapy + Tshark + Hping3 + Mininet
- **Use Cases:**  
  - Train/test ML and DL models for intrusion detection  
  - Analyze abnormal patterns in SDN

---

## 📧 Contact

For questions or access to additional files (raw data, labeled flows), please contact:  
📨 23520964@mg.uit.edu.vn

