## hello, I am kafka.

First-year Cybersecurity & CS student and aspiring security / AI researcher who likes taking things apart to see how they break.

**[metamorphs.dev](https://metamorphs.dev)**: portfolio, projects & write-ups

```console
$ whoami
kafka: student, aspiring cybersecurity / AI researcher

$ cat roadmap.txt
[1] build foundations  →  [2] PhD  →  [3] security / AI research

$ ls ~/stack
python  rust  scapy  pyside6  tauri  jupyter
```

### featured

**[lethe](https://github.com/kafkaesqueismn/lethe)** · *Rust + Tauri*\
A private messenger designed to have **no user identifiers**: no accounts, phone numbers or usernames. Contacts connect through anonymous one-way queues on relays (SimpleX-style), with Double Ratchet end-to-end encryption, certificate-pinned TLS 1.3, fixed-size padded frames and optional Tor.

```console
$ cat lethe/status.txt
stage   early prototype, in active development
now     rough edges, missing features, breaking changes
        crypto not yet independently audited
        not ready for real use yet
goal    a fully fledged messenger for desktop and mobile

[1] prototype  ← you are here  →  [2] fully fledged app
```

**[deobfuscator](https://github.com/kafkaesqueismn/deobfuscator)** · *Python, stdlib only*\
A multi-decoder for CTFs and malware triage: Base64, Base32, hex, URL, ROT13 and single-byte XOR brute force, with a chain mode that peels layered encodings automatically.

```console
$ python3 deobf.py --chain -f samples/chain_deep.txt
#1  url -> base64 -> rot13 -> base32   (score 1.00)
    flag{peel_the_onion_one_layer_at_a_time}
```

### projects by area

| area | repo | what it does |
| --- | --- | --- |
| **crypto** | [pgp-messenger](https://github.com/kafkaesqueismn/pgp-messenger) | Desktop GUI for encrypting, decrypting, signing and verifying messages & files with OpenPGP (PGPy + PySide6) |
| | [cipher-toolkit](https://github.com/kafkaesqueismn/cipher-toolkit) | Classical ciphers (Caesar, Vigenère, XOR) and the attacks that break them |
| **malware / RE** | [static-analyser](https://github.com/kafkaesqueismn/static-analyser) | Inspects files without running them: hashes, file type, PE/ELF headers, entropy, strings, IOCs |
| **blue team** | [pcap-analyser](https://github.com/kafkaesqueismn/pcap-analyser) | Scapy CLI that hunts packet captures for port scans, DNS tunnelling, cleartext creds and unusual ports |
| | [log-analyser](https://github.com/kafkaesqueismn/log-analyser) | Hunts SSH auth logs for brute-force attempts and suspicious logins |
| | [password-checker](https://github.com/kafkaesqueismn/password-checker) | Scores password strength and checks breaches via HIBP's k-anonymity API |
| **ML × security** | [network-scan-detector](https://github.com/kafkaesqueismn/network-scan-detector) | Notebook training a decision tree to detect port scans: a first step into ML for security |

Also into **offense** (red teaming, penetration testing) and, increasingly, **AI security**.

### currently learning

- Linux internals & privilege escalation
- Networking fundamentals and Active Directory attacks
- x86/x64 assembly for reverse engineering
- CTFs and HackTheBox / TryHackMe labs

### goals

- [ ] OSCP
- [ ] Land a security / research internship
- [ ] Publish a write-up or small piece of research
- [ ] PhD in security / AI security

---

<sub>*"A cage went in search of a bird."* — still searching for bugs.</sub>
