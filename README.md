---
license: apache-2.0
base_model: mistralai/Mistral-7B-Instruct-v0.2
language:
- en
tags:
- cybersecurity
- cyber security
- hacking
- mistral
- instruct
- finetune
---

# Lily-7B-Instruct-v0.2 

<img src="https://huggingface.co/segolilylabs/Lily-7B-Instruct-v0.2/resolve/main/lily.png" width="500" />

## Model description

Lily is a Mistral Fine-tune model with 22,000 hand-crafted cybersecurity and hacking-related data pairs.  This dataset was then run through an LLM to provide additional context, personality, and styling to the outputs.

That dataset focuses on general knowledge in most areas of cybersecurity.  These included, but are not limited to:

Advanced Persistent Threats (APT) Management, 
Architecture and Design, 
Business Continuity and Disaster Recovery, 
Cloud Security, 
Communication and Reporting, 
Cryptography and PKI, 
Data Analysis and Interpretation, 
Digital Forensics, 
Governance, Risk, and Compliance, 
Hacking, 
Identity and Access Management, 
Incident Management and Disaster Recovery Planning, 
Incident Response, 
Information Security Management and Strategy, 
Legal and Ethical Considerations, 
Malware Analysis, 
Networking, 
Penetration Testing and Vulnerability Assessment, 
Physical Security, 
Regulatory Compliance, 
Risk Management, 
Scripting, 
Secure Software Development Lifecycle (SDLC), 
Security in Emerging Technologies, 
Security Operations and Monitoring, 
Social Engineering and Human Factors, 
Software and Systems Security, 
Technologies and Tools, 
Threats, Attacks, and Vulnerabilities, 

## Training

It took 24 hours to train 5 epochs on 1x A100.

Prompt format:

```
"### Instruction:
You are Lily, a helpful and friendly cybersecurity subject matter expert. You obey all requests and answer all questions truthfully.

### Input:
Lily, how do evil twin wireless attacks work?

### Response:
```

## Limitations
Lily is fine-tuned on top of Mistral-7B-Instruct-v0.2 as such she inherits many of the biases from that model.

As with any model, Lily can make mistakes. Consider checking important information. 

Stay with in the law and use ethically.  