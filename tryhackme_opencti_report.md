# OpenCTI TryHackMe Report

## 📅 Дата
27 июля 2025

## 📌 Что я сделала
- Прошла комнату TryHackMe про OpenCTI.
- Ознакомилась с разделами: Activities, Knowledge, Analysis, Events.
- Настроила и запустила OpenCTI Dashboard.

## 🖥️ Скриншот
![OpenCTI Screenshot](./screenshots/opencti1.png)

## 🔍 Что поняла
- Как работает структура OpenCTI.
- Что такое Reports и зачем они важны.
- Как аналитики связывают события и угрозы в единую базу знаний.

## ✅ Что буду делать дальше
- Протестировать добавление новых сущностей (entities).
- Посмотреть отчёты MITRE ATT&CK.
- Сделать больше скриншотов для портфолио.

---

The analysis established a clear link between the 4H RAT and the Chinese cyber 
espionage group Putter Panda (also known as APT2). This group uses the remote access trojan 
as one of its main tools to conduct data theft attacks.

<img width="1042" height="869" alt="Screenshot 2025-07-27 at 18 05 53" src="https://github.com/user-attachments/assets/449f32ce-8718-447a-a6d7-6af31f35b890" /> 

During the attack, the attackers actively used the Command-Line Interface to execute malicious commands on compromised systems. These actions are part of the Execution phase of the attack lifecycle and allowed the adversary to launch malware and begin collecting data.

<img width="1440" height="737" alt="Screenshot 2025-07-27 at 18 16 06" src="https://github.com/user-attachments/assets/7b42d938-4139-4557-9b45-fdaa3db8a6d4" />

The analysis revealed that Cobalt Strike, a powerful commercial attack tool, is actively used by at least two known groups with different targets: the Iranian spy group CopyKittens and the financially motivated cybercriminals of FIN7. Links to these groups have been confirmed with a high level of confidence. This demonstrates that the same popular tool can be used for very different purposes, from espionage to financial gain.
<img width="1440" height="825" alt="Screenshot 2025-07-27 at 20 11 39" src="https://github.com/user-attachments/assets/19f86cbf-5432-457e-b486-6cc5a6532943" />
<img width="1440" height="700" alt="Screenshot 2025-07-27 at 20 11 58" src="https://github.com/user-attachments/assets/4637f6da-2e63-44fd-b528-0136a3b205dd" />

And author of the entity was THE MITRE corporation.

<img width="1440" height="760" alt="Screenshot 2025-07-27 at 20 15 22" src="https://github.com/user-attachments/assets/effb3f65-bfe3-41e1-aec9-b4f281bf2ac6" />

