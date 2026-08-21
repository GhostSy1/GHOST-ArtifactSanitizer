# GHOST-ArtifactSanitizer

Evidence sanitization, PII redaction, and log cleaning utility. Developed by Abdulaziz (Ghost-SY1).

## Overview

`GHOST-ArtifactSanitizer` is a specialized tool designed for authorized red team and penetration testing engagements. It inspects local evidence files and configuration exports, computes SHA-256 integrity hashes, identifies observable indicators, and generates structured reports without executing untrusted code or making network requests.

## Installation & Setup

```bash
git clone https://github.com/GhostSy1/GHOST-ArtifactSanitizer.git
cd GHOST-ArtifactSanitizer
python3 main.py --help
```

## Usage

```bash
python3 main.py --input ./target_dir --output report.json --sarif report.sarif
```
