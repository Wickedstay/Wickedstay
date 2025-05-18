# GhostCloak Pro - Hardened Edition

GhostCloak Pro is a fully automated, hardened anonymity framework for Kali Linux, designed to cloak your digital fingerprint, enforce Tor-only routing, and apply anti-forensic countermeasures — all with a single command.

## Features

- Full Tor gateway enforcement with DNS leak protection
- obfs4 bridge support with fallback to Meek or Snowflake
- MAC address spoofing at boot
- RAM-only temporary directories (anti-forensics)
- Encrypted trapdoor + decoy user environment
- Firewall lockdown for traffic leaks
- Automatic Tor Browser installation + isolated config
- Proxychains + pluggable transports support
- Panic trigger & emergency wipe option
- Hardened persistence: all logs auto-wiped, all volatile paths secured

⸻

Requirements
	•	Kali Linux (Rolling or latest)
	•	Root privileges or sudo
	•	Internet connection (initial setup)
	•	Optional: Custom obfs4 bridges for Tor

⸻

Notes
	•	The script self-erases post-install for security.
	•	Logs are stored temporarily in RAM and never written to disk.
	•	Bridge lines can be configured in /etc/tor/torrc after first run.
	•	For paranoid setups, run this VM in Host-Only mode with no persistence.

⸻

Legal Notice

For educational and lawful security research use only. You are responsible for complying with local laws and regulations. The author is not liable for misuse.

⸻

License

MIT License — see LICENSE.md for full details.
