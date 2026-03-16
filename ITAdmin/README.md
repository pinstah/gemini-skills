# ITAdmin Skill for Gemini CLI

Specjalistyczna umiejętność (skill) dla Gemini CLI, koncentrująca się na profesjonalnej administracji systemami IT, infrastrukturą sieciową oraz automatyzacją procesów administracyjnych.

## Przeznaczenie

Skill `ITAdmin` przekształca Gemini w eksperta ds. systemów Windows i Linux. Jest idealny do:
- **Rozwiązywania problemów (Troubleshooting)**: Diagnoza błędów Active Directory, logów systemowych i problemów sieciowych.
- **Automatyzacji**: Generowanie bezpiecznych i zoptymalizowanych skryptów PowerShell oraz Bash.
- **Konfiguracji**: Wsparcie w wdrażaniu ról serwerowych (DNS, DHCP, IIS, Nginx) oraz usług katalogowych.
- **Bezpieczeństwa**: Hardening systemów zgodnie ze standardami CIS oraz zarządzanie politykami GPO.

## Zakres kompetencji

### 🖥️ Windows & Active Directory
- Zarządzanie użytkownikami, grupami i jednostkami organizacyjnymi (OU).
- Tworzenie i diagnostyka polityk grup (GPO).
- Konfiguracja usług: DNS, DHCP, NPS, DFS, SMB.
- PowerShell Remoting i automatyzacja zadań AD.

### 🐧 Linux / UNIX
- Administracja serwerami Ubuntu, Debian, CentOS/RHEL.
- Konfiguracja serwerów WWW (Nginx, Apache) i baz danych.
- Zarządzanie usługami (systemd) i zadaniami (cron).
- Bezpieczeństwo: UFW, iptables, SSH Hardening.

### 🌐 Sieci & VPN
- Diagnostyka stosu TCP/IP.
- Konfiguracja tuneli VPN (WireGuard, OpenVPN, IPsec).
- Analiza ruchu sieciowego i skanowanie portów (nmap, tcpdump).

## Jak używać?

Skill może być aktywowany automatycznie przez Gemini CLI, gdy zadasz pytanie dotyczące administracji IT, lub wywołany bezpośrednio (jeśli konfiguracja CLI na to pozwala).

**Przykładowe zapytania:**
> "Jak zdiagnozować błąd replikacji Active Directory (1722)?"
> "Napisz skrypt Bash, który co noc robi backup bazy MySQL i wysyła go na zewnętrzny serwer SSH."
> "Jak zabezpieczyć serwer SSH na Ubuntu 22.04?"
> "Utwórz politykę GPO blokującą dostęp do Panelu Sterowania dla wybranych użytkowników."

## Standardy odpowiedzi

Każda odpowiedź wygenerowana przy użyciu tego skilla zawiera:
1. **Analizę kontekstu**: Pytanie o konkretne wersje systemów.
2. **Bezpieczeństwo**: Uwzględnienie zasady najniższych uprawnień.
3. **Gotowe rozwiązanie**: Kompletny kod/skrypt z komentarzami.
4. **Weryfikację**: Komendę pozwalającą sprawdzić, czy rozwiązanie działa (np. `dcdiag`, `systemctl status`).

---
*Autor: pinstah*
*Repozytorium: [gemini-skills](https://github.com/pinstah/gemini-skills)*
