# VoLTE Test Case

이 문서는 **4G 및 5G-NSA** 환경에서의 **VoLTE(Voice over LTE)** 테스트 케이스 목록을 관리합니다.

## 1. 개요 (Overview)
* **Technology:** 4G, 5G-NSA
* **Category:** VoLTE
* **Key Scenarios:** Call Success Rate, Mobility, Simultaneous Data, 3-Way Call

---

## 2. 테스트 케이스 목록 (Full List: 1-38)

| ID | Test Case Title (Name) | Category | Technology |
|:---:|:--- |:---:|:---:|
| TC-01 | VoLTE UE2 starts call, UE1 ends | VoLTE | 4G |
| TC-02 | VoLTE UE2 starts and ends call | VoLTE | 4G |
| TC-03 | VoLTE UE1 starts call, UE2 ends | VoLTE | 4G |
| TC-04 | VoLTE UE1 starts and ends call | VoLTE | 4G |
| TC-05 | VoLTE Stationary Test (Poor/Good/Fair/Excellent position) | VoLTE | 4G |
| TC-06 | VoLTE Stability (LTE+NR) | VoLTE | 5G-NSA |
| TC-07 | VoLTE Stability (LTE) | VoLTE | 4G |
| TC-08 | VoLTE Call with mute function | VoLTE | 4G |
| TC-09 | VoLTE Call Success Ratio | VoLTE | 4G |
| TC-10 | VoLTE Call Performance (Idle Mode) - VoLTE MO -> MT | VoLTE | 4G |
| TC-11 | VoLTE Call Performance (Idle Mode) - VoLTE MO -> MT (2) | VoLTE | 4G |
| TC-12 | VoLTE Call Performance (Connected Mode) - VoLTE MO -> MT | VoLTE | 4G |
| TC-13 | VoLTE Call Performance - VoLTE MO -> GSM/CDMA MT | VoLTE | 4G |
| TC-14 | VoLTE Call Performance - GSM/CDMA MO -> VoLTE MT | VoLTE | 4G |
| TC-15 | VoLTE Call Performance - VoLTE MO -> VoLTE MT-FDD | VoLTE | 5G-NSA, 4G |
| TC-16 | VoLTE Call Performance (General) | VoLTE | 5G-NSA, 4G |
| TC-17 | VoLTE + Packet Data | VoLTE | 4G |
| TC-18 | VoLTE (Longrun Call Test) | VoLTE | 4G |
| TC-19 | VoLTE Call with during UDP (with Idle mode) (LTE+NR) | VoLTE | 5G-NSA |
| TC-20 | VoLTE Call with during UDP (with Idle mode) (LTE) | VoLTE | 4G |
| TC-21 | VoLTE Call with during UDP (with Connected mode) (LTE+NR) | VoLTE | 5G-NSA |
| TC-22 | VoLTE Call with during UDP (with Connected mode) (LTE) | VoLTE | 4G |
| TC-23 | Upgrade VoLTE Call to ViLTE-FDD/TDD | VoLTE | 4G |
| TC-24 | Simultaneous VoLTE and NSA Data (VoLTE first, Data next) | VoLTE | 5G-NSA, 4G |
| TC-25 | Simultaneous VoLTE and NSA Data (Data first, VoLTE next) | VoLTE | 5G-NSA, 4G |
| TC-26 | Simultaneous VoLTE and LTE nCA Data (VoLTE MO -> VoLTE MT) | VoLTE | 4G |
| TC-27 | Simultaneous VoLTE and LTE Data (VoLTE MO -> VoLTE MT) | VoLTE | 5G-NSA |
| TC-28 | Simultaneous VoLTE + LTE Data + SMS (VoLTE <-> VoLTE) | VoLTE | 4G |
| TC-29 | MO-MT Voice call success rate in Near/Mid/Far cell | VoLTE | 5G-NSA |
| TC-30 | MO-MT Voice call success rate during mobility | VoLTE | 5G-NSA |
| TC-31 | MO-MT Video call success rate in Near/Mid/Far cell | VoLTE | 5G-NSA |
| TC-32 | MO-MT Video call success rate during mobility | VoLTE | 5G-NSA |
| TC-33 | Long voice call during mobility | VoLTE | 5G-NSA |
| TC-34 | Long video call during mobility | VoLTE | 5G-NSA |
| TC-35 | HD Voice Integrity Verification under LTE Band EN-DC | VoLTE | 5G-NSA |
| TC-36 | Downgrade ViLTE call to VoLTE call-FDD/TDD | VoLTE | 4G |
| TC-37 | 3-Way VoLTE Calling (Call Conference)-FDD/TDD | VoLTE | 4G |
| TC-38 | 3-Way - Receive Incoming VoLTE call when ViLTE is ongoing | VoLTE | 4G |