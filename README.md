# Computer-Networks
# 🌐 Computer Networks & Infrastructure

This repository serves as a centralized hub for my work in computer networking, covering everything from core theoretical concepts (OSI Model, TCP/IP) to hands-on network automation and virtualization labs.

## 🚀 Key Projects
*   **[ Network Setup]** - How to setup a computer network
*   **[ Enterprise Topology]** - A multi-site OSPF/BGP architecture built in GNS3.
*   **[Network-Automation-Scripts]** - Python scripts using Netmiko for automated VLAN provisioning.
*   **[Packet-Analysis-Portfolio]** - A collection of Wireshark (.pcap) analyses focusing on TCP handshakes and DNS troubleshooting.

## 🛠 Tech Stack & Tools
*   **Simulators**: [GNS3](https://www.gns3.com), [Cisco Modeling Labs (CML)](https://www.cisco.com), EVE-NG.
*   **Automation**: Ansible, Python (Netmiko, Nornir), Terraform.
*   **Analysis**: Wireshark, Nmap, iPerf.
*   **Infrastructure**: Cisco IOS/XE, Arista EOS, Juniper Junos.

## 📂 Repository Structure
```text
├── labs/               # Topologies and configuration files
│   ├── ospf-multi-area/
│   └── bgp-evpn-vxlan/
├── scripts/            # Automation and monitoring tools
│   ├── backup_configs.py
│   └── health_check.yml
├── docs/               # Network diagrams and troubleshooting logs
└── pcaps/              # Packet capture files for protocol analysis



# 🌐 컴퓨터 네트워크 및 인프라 (Computer Networks & Infrastructure)

이 저장소는 OSI 모델, TCP/IP와 같은 핵심 이론부터 네트워크 자동화 및 가상화 실습에 이르기까지, 제가 진행한 모든 네트워크 엔지니어링 프로젝트를 기록하는 공간입니다.

## 🚀 주요 프로젝트
*   **[실습 1: 엔터프라이즈 토폴로지]** - GNS3로 구축한 다중 사이트 OSPF/BGP 아키텍처.
*   **[네트워크 자동화 스크립트]** - Netmiko 라이브러리를 활용한 자동 VLAN 프로비저닝 파이썬 스크립트.
*   **[패킷 분석 포트폴리오]** - TCP 핸드쉐이크 및 DNS 트러블슈팅 중심의 Wireshark(.pcap) 분석 모음.

## 🛠 사용 기술 및 도구 (Tech Stack)
*   **시뮬레이터**: [GNS3](https://www.gns3.com), [Cisco Modeling Labs (CML)](https://www.cisco.com), EVE-NG.
*   **자동화 도구**: Ansible, Python (Netmiko, Nornir), Terraform.
*   **분석 도구**: Wireshark, Nmap, iPerf.
*   **인프라 장비**: Cisco IOS/XE, Arista EOS, Juniper Junos.

## 📂 저장소 구조
```text
├── labs/               # 토폴로지 파일 및 장비 설정값 (Config)
│   ├── ospf-multi-area/
│   └── bgp-evpn-vxlan/
├── scripts/            # 자동화 및 모니터링 툴
│   ├── backup_configs.py
│   └── health_check.yml
├── docs/               # 네트워크 구성도 및 트러블슈팅 로그
└── pcaps/              # 프로토콜 분석을 위한 패킷 캡처 파일
