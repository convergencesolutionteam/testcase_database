# Handover Test Case

이 문서는 **4G/5G/Wi-Fi** 환경에서의 다양한 **Handover(이동성)** 테스트 케이스 목록을 포함합니다.

## 1. 개요 (Overview)
* **Technology:** 5G-SA, 5G-NSA, 4G, Wi-Fi, Multi-RAT
* **Category:** Handover
* **Key Scenarios:** Xn/N2 HO, Intra/Inter-band, Voice/Data Continuity

---

## 2. 테스트 케이스 목록 (# : 119)

| ID | Test Case Title (Name) | Category | Technology |
|:---:|:--- |:---:|:---:|
| 01 | Xn Handover Latency & Success Rate | Handover | 5G-SA |
| 02 | Wi-Fi -> Weak LTE Handover Voice Call | Handover | 4G, Wifi |
| 03 | VoNR <-> VoWiFi Handover | Handover | 5G-SA |
| 04 | VoNR - Intra-Distributed Unit (DU) handover | Handover | 5G-SA |
| 05 | VoNR - Intra-CU Inter-DU handover | Handover | 5G-SA |
| 06 | VoNR - Inter-Central Unit (CU) handover | Handover | 5G-SA |
| 07 | VoLTE Handover Test (intra) | Handover | 4G |
| 08 | ViLTE Handover Test (intra) | Handover | 4G |
| 09 | Video Streaming - Handover between same MeNB but different O-DUs - Inter O-DU Intra O-CU | Handover | 5G-NSA |
| 10 | Video Streaming - Handover between same MeNB but different O-CUs - Inter O-CU | Handover | 5G-NSA |
| 11 | Video Streaming - Handover between same Master eNB but different O-RUs - Intra O-DU | Handover | 5G-NSA |
| 12 | Video Streaming - Handover between different MeNB while staying connected to same SgNB | Handover | 5G-NSA |
| 13 | Verify successful Re-est in source cell during X2 HO execution Inter Frequency HO | Handover | 5G-SA,5G-NSA,4G |
| 14 | UE Level Ping-pong HO Minimization for NR | Handover | 5G-SA |
| 15 | UE Assisted ANR - inter-eNB (LTE <-> LTE) | Handover | 4G |
| 16 | UE Assisted ANR - inter-eNB - Macro <-> Femto (LTE <-> LTE) | Handover | 4G |
| 17 | SA HO Intra-band Handover TCP DL | Handover | 5G-SA |
| 18 | SA HO Inter-band Handover TCP DL | Handover | 5G-SA |
| 19 | PSCell Change Verification Test | Handover | 5G-NSA |
| 20 | Pcell handover with 5G Change | Handover | 5G-NSA |
| 21 | Nbr Source Type Information Check | Handover | 4G |
| 22 | N2 Handover Latency & Success Rate | Handover | 5G-SA |
| 23 | MeNB Handover with/without SgNB Release | Handover | 5G-NSA |
| 24 | Measurement configuration – Event A1/A2/A3/A4/A5/B1/B2 | Handover | 5G-NSA |
| 25 | LTE_Intrafreq HO | Handover | 4G |
| 26 | LTE_Intraband HO | Handover | 4G |
| 27 | LTE_Interfreq HO | Handover | 4G |
| 28 | LTE_Interband HO | Handover | 4G |
| 29 | LTE(MNO/MSO) <-> Wi-Fi Mobility with OTT App Data Running | Handover | 4G,Wifi |
| 30 | LTE to NR Data Handover Verification | Handover | 5G-NSA |
| 31 | LTE HO Intra-band Handover TCP DL | Handover | 4G |
| 32 | LTE HO Inter-band Handover TCP DL | Handover | 4G |
| 33 | LTE -> Wi-Fi Handover Voice Call | Handover | 4G,Wifi |
| 34 | LTE -> Wi-Fi -> LTE Handover Voice Call | Handover | 4G,Wifi |
| 35 | Intra-frequency S1 HO with ANR (Ping&VoLTE) | Handover | 4G |
| 36 | Intra-frequency Reselection Test | Handover | 5G-SA |
| 37 | Intra-frequency Handover Test | Handover | 5G-SA |
| 38 | intra-frequency handover | Handover | 4G |
| 39 | Intra-frequency (X2, LTE+NR) Handover (with UL TCP) | Handover | 5G-NSA |
| 40 | Intra-frequency (X2, LTE+NR) Handover (with DL TCP) | Handover | 5G-NSA |
| 41 | Intra-frequency (X2, LTE+NR) Handover (Max UEs) | Handover | 5G-NSA |
| 42 | Intra-frequency (X2, LTE) Handover (with UL TCP) | Handover | 4G |
| 43 | Intra-frequency (X2, LTE) Handover (with DL TCP) | Handover | 4G |
| 44 | Intra-frequency (S1, LTE+NR) Handover (with UL TCP) | Handover | 5G-NSA |
| 45 | Intra-frequency (S1, LTE+NR) Handover (with DL TCP) | Handover | 5G-NSA |
| 46 | Intra-frequency (S1, LTE+NR) Handover (Max UEs) | Handover | 5G-NSA |
| 47 | Intra-frequency (S1, LTE) Handover (with VoLTE) | Handover | 4G |
| 48 | Intra-frequency (S1, LTE) Handover (with UL TCP) | Handover | 4G |
| 49 | Intra-frequency (S1, LTE) Handover (with DL TCP) | Handover | 4G |
| 50 | Intra-frequency (Band) Xn based Handover with TCP/UDP bi-directional Tput | Handover | 5G-SA |
| 51 | Intra-frequency (Band) Xn based Handover | Handover | 5G-SA |
| 52 | Intra-frequency (Band) N2 based Handover with TCP/UDP bi-directional Tput | Handover | 5G-SA |
| 53 | Intra-frequency (Band) N2 based Handover | Handover | 5G-SA |
| 54 | inter-frequency handover | Handover | 4G |
| 55 | Inter-frequency (S1, LTE+NR) Handover (with UL TCP) | Handover | 5G-NSA |
| 56 | Inter-frequency (S1, LTE+NR) Handover (with DL TCP) | Handover | 5G-NSA |
| 57 | Inter-frequency (S1, LTE+NR) Handover (Max UEs) | Handover | 5G-NSA |
| 58 | Inter-frequency (S1, LTE) Handover (with VoLTE) | Handover | 4G |
| 59 | Inter-frequency (S1, LTE) Handover (with UL TCP) | Handover | 4G |
| 60 | Inter-frequency (S1, LTE) Handover (with DL TCP) | Handover | 4G |
| 61 | Inter-frequency (Band) Xn based Handover with TCP/UDP bi-directional Tput | Handover | 5G-SA |
| 62 | Inter-frequency (Band) Xn based Handover | Handover | 5G-SA |
| 63 | Inter-frequency (Band) N2 based Handover with TCP/UDP bi-directional Tput | Handover | 5G-SA |
| 64 | Inter-frequency (Band) N2 based Handover | Handover | 5G-SA |
| 65 | Inter-cell EN-DC Data Handover Verification | Handover | 5G-NSA |
| 66 | Inter Vendor Xn Hand over support | Handover | 5G-SA |
| 67 | Inter Vendor N2 Hand over support | Handover | 5G-SA |
| 68 | Idle Mode Intra- O-DU mobility_Intra frequency | Handover | 5G-NSA |
| 69 | Idle Mode Inter- O-DU mobility_Intra frequency | Handover | 5G-NSA |
| 70 | Idle Mode Inter- O-CU mobility_Intra frequency | Handover | 5G-NSA |
| 71 | HO (SA -> LTE)- Inter-gNB Inter-frequency - SA - Band -> Band | Handover | 5G-SA |
| 72 | HO (bi-directional)- Intra-gNB intra-frequency - SA - Band <-> Band | Handover | 5G-SA |
| 73 | HO (bi-directional)- Intra-gNB Inter-frequency - SA - Band <-> Band | Handover | 5G-SA |
| 74 | HO (bi-directional)- Intra-gNB Inter-frequency - SA | Handover | 5G-SA |
| 75 | HO (bi-directional)- Intra-eNB intra-frequency - NSA - Band <-> Band | Handover | 5G-NSA |
| 76 | HO (bi-directional)- Intra-eNB intra-frequency - NSA | Handover | 5G-NSA |
| 77 | HO (bi-directional)- Intra-eNB intra-frequency - LTE - Band <-> Band | Handover | 4G |
| 78 | HO (bi-directional)- Intra-eNB intra-frequency - LTE - Band <-> Band (2) | Handover | 4G |
| 79 | HO (bi-directional)- Intra-eNB intra-frequency - LTE | Handover | 4G |
| 80 | HO (bi-directional)- Intra-eNB Inter-frequency - NSA - Band <-> Band | Handover | 5G-NSA |
| 81 | HO (bi-directional)- Intra-eNB inter-frequency - LTE - Band <-> Band | Handover | 4G |
| 82 | HO (bi-directional)- Intra-eNB inter-frequency - LTE | Handover | 4G |
| 83 | HO (bi-directional)- Inter-gNB intra-frequency - SA - Band <-> Band | Handover | 5G-SA |
| 84 | HO (bi-directional)- Inter-gNB intra-frequency - SA | Handover | 5G-SA |
| 85 | HO (bi-directional)- Inter-gNB Inter-frequency - SA - Band <-> Band | Handover | 5G-SA |
| 86 | HO (bi-directional)- Inter-gNB Inter-frequency - SA | Handover | 5G-SA |
| 87 | HO (bi-directional)- Inter-eNB intra-frequency - NSA - Band <-> Band | Handover | 5G-NSA |
| 88 | HO (bi-directional)- Inter-eNB intra-frequency - NSA | Handover | 5G-NSA |
| 89 | HO (bi-directional)- Inter-eNB intra-frequency - LTE - Band <-> Band | Handover | 4G |
| 90 | HO (bi-directional)- Inter-eNB intra-frequency - LTE - Band <-> Band (2) | Handover | 4G |
| 91 | HO (bi-directional)- Inter-eNB intra-frequency - LTE | Handover | 4G |
| 92 | HO (bi-directional)- Inter-eNB Inter-frequency - NSA - Band <-> Band | Handover | 5G-NSA |
| 93 | HO (bi-directional)- Inter-eNB inter-frequency - LTE - Band <-> Band | Handover | 4G |
| 94 | HO - VoNR + Data - (bi-directional)- Inter-eNB Inter-frequency - SA-Band | Handover | 5G-SA |
| 95 | HO - VOLTE + Data - (bi-directional)- Inter-eNB Inter-frequency - NSA | Handover | 5G-NSA |
| 96 | HO - VOLTE + Data (bi-directional)- Inter-eNB Inter-frequency - LTE | Handover | 4G |
| 97 | HO - EPS-FB Call + Data - (bi-directional)- Inter-eNB Inter-frequency - SA-Band | Handover | 5G-SA |
| 98 | generic handover | Handover | 4G |
| 99 | EPS to 5GS Idle Mobility Verification Test (N26 Interface) | Handover | Multi-RAT(5G-4G) |
| 100 | EPS to 5GS Handover Verification Test (N26 Interface) | Handover | Multi-RAT(5G-4G) |
| 101 | EPS to 5GS Re-direction Verification Test (N26 Interface) | Handover | Multi-RAT(5G-4G) |
| 102 | EPS to 5GS Idle Mobility Verification (without N26 Interface) | Handover | Multi-RAT(5G-4G) |
| 103 | EN-DC Cell to LTE-only Cell Data Handover Verification | Handover | 5G-NSA |
| 104 | eMTC S1 Intra-frequency S1 HO | Handover | 4G |
| 105 | Connected mode Intra O-DU mobility - HO | Handover | 5G-SA,5G-NSA |
| 106 | Connected mode Inter O-DU mobility - HO | Handover | 5G-SA,5G-NSA |
| 107 | Connected mode Inter O-CU mobility - HO | Handover | 5G-SA,5G-NSA |
| 108 | Connected Mode Handover with voice call and data | Handover | 5G-NSA |
| 109 | Beam Switching due to UE Mobility on the same PCI | Handover | 5G-SA |
| 110 | A2 at cell edge Critical Threshold with A5 | Handover | 5G-SA |
| 111 | 5GS to EPS Re-direction Verification Test (N26 Interface) | Handover | Multi-RAT(5G-4G) |
| 112 | 5GS to EPS Idle Mobility Verification Test (N26 Interface) | Handover | Multi-RAT(5G-4G) |
| 113 | 5GS to EPS Idle Mobility Verification (without N26 Interface) | Handover | Multi-RAT(5G-4G) |
| 114 | 5GS to EPS Handover Verification Test (N26 Interface) | Handover | Multi-RAT(5G-4G) |
| 115 | 5G_SCG Modification HO | Handover | 5G-NSA |
| 116 | 5G_MCG Intrafreq HO | Handover | 5G-SA |
| 117 | 5G_MCG Interfreq HO | Handover | 5G-SA |
| 118 | 5G Handover | Handover | 5G-SA |
| 119 | 5G Change | Handover | 5G-NSA |