# Владимир Бурдин

Специалист по информационной безопасности с практической подготовкой в защите Linux- и Windows-инфраструктуры.

Прошёл профессиональную переподготовку по программе «Специалист по информационной безопасности» в Яндекс Практикуме. В учебных проектах и дипломной работе проектировал и настраивал защищённые лабораторные инфраструктуры, автоматизировал защитные задачи, выполнял проверки и документировал результаты.

🟢 **Open to work** — рассматриваю стартовые позиции в информационной безопасности, инфраструктурной безопасности и системном администрировании с задачами ИБ.

> **English summary:** Entry-level Information Security Specialist with hands-on experience building and securing isolated Linux and Windows lab infrastructures. Open to work.

## Ключевые навыки

### ОС, инфраструктура и автоматизация

- Linux: Ubuntu, Debian
- Windows Server, Windows 10/11
- Docker, Docker Compose, VirtualBox
- Python, Bash, PowerShell
- Ansible, Git, GitHub, YAML, JSON
- SSH, systemd, rsyslog, logrotate

### Управление доступом

- Active Directory, OU, группы безопасности, GPO
- OpenLDAP, LDAP
- PAM, SSSD, sudo, RBAC
- Сервисные учётные записи, POSIX ACL, Samba/SMB

### Сети и защита периметра

- TCP/IP, DNS, сегментация сети, DMZ
- nftables, NAT, DNAT, SNAT, принцип `default deny`
- WireGuard: удалённый доступ и site-to-site VPN
- Nginx, ModSecurity, OWASP CRS, BunkerWeb

### Мониторинг и диагностика

- Wazuh: анализ логов, Vulnerability Detection, IOC, Active Response
- ClamAV, EICAR, анализ журналов событий
- CVE, MITRE ATT&CK, OWASP Top 10
- Nmap, Wireshark, curl, nslookup, smbclient
- Arkime, PolarProxy, Draw.io

## Обучение

**Яндекс Практикум — профессиональная переподготовка**  
Специалист по информационной безопасности, 2026.

В рамках программы выполнил учебные проекты и дипломную работу по проектированию, настройке и проверке защищённой инфраструктуры в изолированной лабораторной среде.

## Проекты по информационной безопасности

| Проект | Краткое содержание | Технологии |
|---|---|---|
| [Реализация безопасной инфраструктуры компании InvestPro](https://github.com/vladimirbr-rgb/investpro-secure-infrastructure) | Проектирование защищённой инфраструктуры, сегментация сети, настройка межсетевого экрана и управления доступом | Linux, Windows Server, Active Directory, OpenLDAP, nftables, WireGuard |
| [Security Operations Lab: Layer 8](https://github.com/vladimirbr-rgb/layer8-security-operations-lab) | Мониторинг и реагирование на инциденты, анализ уязвимостей, WAF, VPN, LDAP и сетевая фильтрация | Wazuh, BunkerWeb, WireGuard, LDAP, nftables, Docker |
| [Дипломный проект: защищённая инфраструктура головного офиса и филиала](https://github.com/vladimirbr-rgb/secure-infrastructure-thesis) | Аудит, расследование инцидентов, Linux hardening, сегментация филиала, nftables, ClamAV через Ansible и тестовый домен Active Directory с GPO | Linux, Windows Server, Active Directory, OpenLDAP, Ansible, nftables, Wazuh, ClamAV, Arkime |

## Практика CTF / HackerLab

Решаю учебные CTF-задачи на платформе [HackerLab](https://hackerlab.pro/categories/misc), чтобы развивать практические навыки анализа артефактов, работы с Linux, Python, криптографическими инструментами и безопасного документирования результатов.

| Задание | Краткое содержание | Практические навыки |
|---|---|---|
| [Anonymizer — Decoding Client Records](https://github.com/vladimirbr-rgb/hackerlab-ctf-writeups/tree/main/task-01) | Анализ Python-скрипта и учебных клиентских артефактов, подготовка собственного декодера и безопасная проверка результата | Ubuntu, Bash, Python, анализ логики обработки данных, `unzip`, работа с файлами |
| [Time Capsule](https://github.com/vladimirbr-rgb/hackerlab-ctf-writeups/tree/main/task-02-time-capsule) | Анализ time-lock контейнера, извлечение age-пейлоада и расшифровка с использованием `age-plugin-tlock` и drand | Windows PowerShell, SSH/SCP, Ubuntu, Bash, `age`, drand, `age-plugin-tlock`, анализ криптографических артефактов |

Полное описание, безопасный журнал команд и подтверждающие скриншоты собраны в отдельном репозитории: [HackerLab CTF Write-ups](https://github.com/vladimirbr-rgb/hackerlab-ctf-writeups).

> Все задачи выполняются только в рамках учебной платформы и на предоставленных артефактах. В публичных write-up'ах не публикуются флаги, ключи, расшифрованные данные, персональная информация и иные чувствительные материалы.

## Инфраструктура и системное администрирование

Практический проект по проектированию и настройке корпоративной инфраструктуры: сетевой дизайн, VLAN, маршрутизация, базовые Linux-сервисы, автоматизация и Active Directory.

| Проект | Краткое содержание | Технологии |
|---|---|---|
| [Superstore Network, Services and Active Directory Lab](https://github.com/vladimirbr-rgb/superstore-network-services-lab) | Проектирование сети головного офиса и даркстора, VLAN, inter-VLAN routing, DHCP, NAT/DNAT, DNS, NTP, Ansible, Postfix, FTP, Nginx и Active Directory | EVE-NG, Cisco IOS, VLAN, 802.1Q, DHCP, NAT/PAT, DNAT, DNS, NTP, Ansible, Postfix, vsftpd, Nginx, Active Directory, GPO |

> Каждый репозиторий содержит описание цели, архитектуру, используемые технологии и результаты проверок, выполненных в изолированной учебной среде.

## Принципы публикации

- Все материалы относятся только к учебным и изолированным лабораторным средам.
- В репозиториях не публикуются реальные IP-адреса, домены, учётные данные, ключи, токены и персональные данные.
- Конфигурации публикуются только в виде безопасных примеров.
- Материалы не предназначены для несанкционированного тестирования чужих систем.

## Контакты

- GitHub: [@vladimirbr-rgb](https://github.com/vladimirbr-rgb)
- Email: [fin-21@mail.ru](mailto:fin-21@mail.ru)
- HH.ru: [резюме Владимира Бурдина](https://hh.ru/resume/f0a4ab52ff111561650039ed1f56506a4b797a)
- Telegram: [@VIBVID](https://t.me/VIBVID)
