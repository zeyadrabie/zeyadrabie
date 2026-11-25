## Hi, I'm Zeyad

I'm a cybersecurity student at UTSA (BBA in Cybersecurity, graduating December 2027), based in Temple, Texas. I'm looking for remote IT and security internships.

### Projects

- **[Roadside Emergencies](https://github.com/zeyadrabie/FS25_RoadsideEmergencies)**: a Farming Simulator 25 mod that adds 19 roadside emergency calls (wrecks, animals in the road, downed power lines) to the game's Emergency Pack. Public beta. Built with Claude Code.
- **[The Dispatch](https://github.com/zeyadrabie/the-dispatch)**: a fleet tracker and voice assistant for American Truck Simulator, built with Python, Flask, Whisper and the Claude API. No longer in active development.

### Open source

Much of my open source work is security-related: authentication and permission checks in NetBox, cookie and subdomain takeover guidance in the OWASP Web Security Testing Guide, and SSL/TLS docs in CPython.

Merged:
- **NetBox**: [enforce SSO allowlist settings in the default auth pipeline](https://github.com/netbox-community/netbox/pull/23619) and [require `change_device` permission to add a virtual chassis member](https://github.com/netbox-community/netbox/pull/23673)
- **OWASP Web Security Testing Guide**: [updated SameSite cookie guidance for current browser behavior](https://github.com/OWASP/wstg/pull/1582), [added the `Partitioned` cookie attribute and third-party cookie defaults](https://github.com/OWASP/wstg/pull/1685) and [updated the subdomain takeover testing methodology](https://github.com/OWASP/wstg/pull/1413)
- **pwndbg**: [dropped support for Python 3.10 and Ubuntu 22.04](https://github.com/pwndbg/pwndbg/pull/4303)
- **CPython**: [linked the tokenizer docs from the `re.Scanner` source](https://github.com/python/cpython/pull/161595)
- **pandas**: [fixed `Styler.to_excel` reading border color names as widths](https://github.com/pandas-dev/pandas/pull/72241) and [added a regression test for boolean ufuncs called with `out=` on masked arrays](https://github.com/pandas-dev/pandas/pull/72100)
- **pypdf**: [used full class names for `pypdf.constants` imports](https://github.com/py-pdf/pypdf/pull/4402), [used PEP 8 names in the encryption module](https://github.com/py-pdf/pypdf/pull/4436), [replaced raw strings with existing constants in `generic/_files.py`](https://github.com/py-pdf/pypdf/pull/4479) and [removed the Ruff `PT011` ignore](https://github.com/py-pdf/pypdf/pull/4493)
- **Reflex**: [reset managed logging between unit tests](https://github.com/reflex-dev/reflex/pull/7901) and [made an explicit `--loglevel info` take effect when INFO is already the level](https://github.com/reflex-dev/reflex/pull/7960)
- **NumPy**: [removed outdated "str or unicode" wording from the `numpy.strings` docs](https://github.com/numpy/numpy/pull/33189)

In review:
- **CPython**: [document that `PROTOCOL_SSLv3` and `PROTOCOL_TLSv1*` aren't available with OpenSSL 4.0+](https://github.com/python/cpython/pull/162084) and [warn about `return` in a loop inside a `finally` block](https://github.com/python/cpython/pull/162591)
- **Redash**: [fix outdated security guidance in the docs](https://github.com/getredash/redash/pull/7910)
- **BleachBit**: [add six languages to the Windows installer](https://github.com/bleachbit/bleachbit/pull/2566)
- **pypdf**: [type-check four more test modules](https://github.com/py-pdf/pypdf/pull/4503) and [remove the Ruff `B905` ignore](https://github.com/py-pdf/pypdf/pull/4512)
- **Reflex**: [rename the toast button style props to Sonner's singular names](https://github.com/reflex-dev/reflex/pull/7988)
- **Sphinx**: [clarify the `obj_type` passed to `autodoc-skip-member`](https://github.com/sphinx-doc/sphinx/pull/14802)

[See all my pull requests](https://github.com/search?q=is%3Apr+author%3Azeyadrabie+-user%3Azeyadrabie&type=pullrequests)

### Coursework

- Fall 2026: Malware Analysis, Cloud Computing (AWS), Telecommunications & Networking
- Spring 2027: Network Security, Information Assurance & Security, Cyber Attack and Defend I
- Completed: Operating Systems Security, Programming I (Python), Programming II (Java)

### Tools I've used in class and projects

Python, Java, Wireshark, Cisco Packet Tracer, YARA, CAPA, AWS

### Contact

[LinkedIn](https://www.linkedin.com/in/zeyad-rabie-913586369) · [sansabadawg@gmail.com](mailto:sansabadawg@gmail.com)
