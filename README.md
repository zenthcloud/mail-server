# Zenth Mail Server

**Zenth Mail Server** is a fully open-source, sovereign mail server solution built as part of the Zenth Cloud ecosystem by Sky Genesis Enterprise. It offers a modular, secure, and privacy-focused platform for handling email communication using open standards like IMAP, SMTP, and POP3.

## ✉️ Features

- ✅ Support for IMAP, SMTP, and POP3 protocols
- ✅ Integrated spam and virus filtering (Rspamd, ClamAV)
- ✅ LDAP/AD integration for user authentication and provisioning
- ✅ Webmail support (SOGo or Roundcube)
- ✅ Domain and alias management via `api-server`
- ✅ DKIM, SPF, DMARC support out of the box
- ✅ Logging and monitoring hooks via `status-server`
- ✅ TLS/SSL encrypted transport for all protocols

## 📦 Part of the Zenth Cloud Stack

Zenth Mail Server is designed to work seamlessly with other Zenth Cloud components:

- `ldap-server` – User and mailbox authentication
- `dns-server` – MX, SPF, DKIM, and DMARC DNS records
- `panel-server` – Web-based admin UI for domains, mailboxes, and quotas
- `status-server` – Live status and health reporting
- `api-server` – Centralized configuration and automation
- `firewall-server` – Network filtering and email flow control

## 🛠️ Technology

- Mail transfer: **Postfix**
- Mail delivery: **Dovecot**
- Webmail: **Roundcube** or **SOGo**
- Spam/Virus: **Rspamd**, **ClamAV**
- Containerized for Proxmox, Docker, or K8s
- Fully compliant with modern email standards

## 📖 Documentation

Documentation and setup guides are available in the `/docs` directory or on [Documentations](https://docs.zenthcloud.com).

## 🛡️ License

This project is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. See the `LICENSE` file for full details.

---

We welcome contributions, issues, and feedback. Fork, star, and join the community at [github.com/zenthcloud](https://github.com/zenthcloud).
