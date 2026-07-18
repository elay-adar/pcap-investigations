# PCAP Investigations

A collection of network traffic (PCAP) analysis case studies — investigating
simulated and real-world malicious traffic using Wireshark, from initial
detection to full incident report.

## Why this repo exists

Every case in this repo starts from a realistic trigger (a SIEM alert, a
suspicious signature hit, a reported incident) and works through to a
completed investigation: identifying the affected host, reconstructing the
attack chain, extracting indicators of compromise, and mapping the behavior
to MITRE ATT&CK.

## How each investigation is structured

Every case lives in its own folder under `investigations/`, following the
same format so they're easy to compare and easy to navigate.