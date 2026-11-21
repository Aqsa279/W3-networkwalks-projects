
# Optional Lab - AI-Assisted Password Cracking with HexStrike MCP

## 1. Project Overview

This project explores AI-assisted password security testing using Claude Desktop, HexStrike MCP Server, and John the Ripper.

The lab demonstrates how an AI assistant can interact with cybersecurity tools through the Model Context Protocol (MCP).

## 2. Objectives

- Understand Model Context Protocol (MCP).
- Set up HexStrike MCP Server.
- Integrate HexStrike with Claude Desktop.
- Verify John the Ripper availability.
- Extract PDF password hashes.
- Perform password recovery in an authorized lab.

## 3. Tools and Technologies

- Kali Linux
- Claude Desktop
- HexStrike AI
- MCP Server
- John the Ripper
- rockyou.txt Wordlist
- Python Virtual Environment

## 4. Lab Environment

Operating System: Kali Linux

AI Assistant: Claude Desktop

MCP Server: HexStrike AI

Password Testing Tool: John the Ripper

## 5. Methodology

### Step 1: Clone HexStrike Repository

```bash
git clone https://github.com/0x4m4/hexstrike-ai.git
cd hexstrike-ai
```

### Step 2: Create Virtual Environment

```bash
python3 -m venv hexstrike-env
source hexstrike-env/bin/activate
```

### Step 3: Install Dependencies

```bash
pip3 install -r requirements.txt
```

### Step 4: Start HexStrike Server

```bash
python3 hexstrike_server.py
```

### Step 5: Configure Claude Desktop

Configure the HexStrike MCP server in Claude Desktop configuration.

### Step 6: Verify MCP Connection

Check whether Claude Desktop can communicate with the HexStrike MCP server.

### Practical Evidence

The Screenshots folder contains evidence of the lab setup,
MCP server configuration, tool integration, and password
recovery process.

### Step 7: Verify John the Ripper

Use Claude to check John the Ripper installation and version.

### Step 8: PDF Hash Extraction

Extract the hash from the authorized training PDF file.

### Step 9: Password Recovery

Use John the Ripper with the rockyou.txt wordlist to test the PDF hash.

### Step 10: Verify Results

Open the authorized PDF using the recovered password.

## 6. Screenshots

<img width="562" height="305" alt="Screenshot 2026-11-19 134910" src="https://github.com/user-attachments/assets/fdb132b6-4944-4f7e-bb23-0593faa0aafb" />
<img width="959" height="497" alt="Screenshot 2026-11-19 164251" src="https://github.com/user-attachments/assets/291eb1af-beae-460f-847a-552a7b7bc935" />


## 7. Learning Outcomes

- Learned MCP architecture and integration.
- Practiced setting up an MCP server.
- Integrated AI with cybersecurity tools.
- Explored AI-assisted password security testing.
- Practiced John the Ripper in a lab environment.

## 8. Security Disclaimer

All activities are intended for educational purposes and authorized security testing only.

## 9. References

HexStrike AI:
https://github.com/0x4m4/hexstrike-ai

Claude Desktop:
https://github.com/aaddrick/claude-desktop-debian

John the Ripper:
https://www.openwall.com/john/

## Author

Aqsa Shafiq

GitHub: https://github.com/Aqsa279

