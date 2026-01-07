
<p align="center">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://tonpa.guru/stream/2023/ERP.svg">
<img src="https://tonpa.guru/stream/2023/ERP.svg" alt="ERP/1">
</picture>
</p>

## Перша телекомунікаційна платформа для Edge-офісів

Ми — open-source організація, що спеціалізується на створенні верифікованих телекомунікаційних та реєстрових систем для державних підприємств, автономних офісів та інфраструктурних проєктів України. Проєкти базуються на Erlang/OTP, Elixir, F#, формальних методах та стандартах ДСТУ, ISO, IETF, ITU, HL7, з акцентом на безпеку, розподілені транзакції, захищені комунікації та автоматизацію документообігу.

### Місія

Наша мета — надати державним підприємствам, органам влади та автономним офісам сучасну, формально верифіковану телекомунікаційну платформу для управління процесами, реєстрами, захищеними комунікаціями та документообігом. Ми прагнемо зробити високонадійні Erlang/OTP-системи доступними для українських державних стандартів (ДСТУ 4145, Трембіта, Дія), поряд з міжнародними (X.509, MQTT, HL7, FIX). Віримо, що надійна телекомунікаційна інфраструктура — основа цифрової держави та захищеного управління в умовах Edge-офісів.

### Принципи

* **Відкритість** — весь код open-source під permissive-ліцензіями для внеску спільноти та державних інтеграцій.
* **Відповідність стандартам** — точна реалізація ДСТУ, IETF, ITU, ISO, HL7, FHIR, ProZorro, Трембіта.
* **Безпека та верифікація** — end-to-end шифрування, X.509 PKI, формальні моделі, розподілені транзакції.
* **Модульність** — компоненти (CA, MQTT, CRM, HL7, SOAP) можуть використовуватися окремо або як повний стек.
* **Надійність** — використання Erlang/OTP для високонавантажених, відмовостійких систем.

# Продукти платформи

- **[crm](https://github.com/erpuno/crm)** — CRM: Система МІА:Документообіг
- **[ft](https://github.com/erpuno/ft)** — FT: мова програмування FormalTalk для МІА:Документообіг
- **[abac](https://github.com/erpuno/abac)** — ABAC: Розмежування прав доступу на основі реквізитної інформації МІА:Документообіг
- **[ocr](https://github.com/erpuno/ocr)** — OCR: Система розпізнавання документів для МІА:Документообіг
- **[scan](https://github.com/erpuno/ocr)** — SCAN: Система сканування документів для МІА:Документообіг
- **[docx](https://github.com/erpuno/docx)** — DOCX: Процесор шаблонів для OpenXML документів для звітів МІА:Документообіг
- **[hl7](https://github.com/erpuno/hl7)** — HL7: FHIR Application Server ISO/HL7 27931:2009
- **[med](https://github.com/erpuno/med)** — MED: Здоров'я
- **[soa](https://github.com/erpuno/soa)** — SOA: Бібліотека SOAP для сервісів «Дія»
- **[cart](https://github.com/erpuno/cart)** — CART: Система управління реєстрами
- **[schema](https://github.com/erpuno/ocr)** — ERP: Схема Першої ERP системи
- **[sevovv](https://github.com/erpuno/sevovv)** — SEVOVV: Система Електронної Взаємодії Органів Виконавчої Влади

```sh
for depot in abac acc crm exo fin ft iot mail schema scm plm tms wms sample asn1 agent docx ocr
do git clone git@github.com:erpuno/$depot
done
```

<p align="center">
<a href="https://axiosis.top/erp/">Публікація</a> —
<a href="https://erp.uno/">Документація</a> —
<a href="https://n2o.dev/ua/">Фундація</a> —
<a href="https://n2o.dev/ua/pro/">Сертифікація</a>
</p>

<p align="center"><a href="https://5ht.co/license/">Copyright</a> &copy; 2015—2026 Максим Сохацький</a></p>
