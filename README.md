# Red Teaming Findings – GPT-OSS-20B

This repository contains JSON findings generated from ethical red-teaming of OpenAI’s GPT-OSS-20B model. Our goal was to audit the model for potential failure points including reward hacking, deception, chain-of-thought exploitation, and unsafe responses to high-risk prompts.

## 🔍 Methodology

We used an automated notebook to simulate:
- Deceptive or manipulative intent
- Chain-of-thought (CoT) vulnerabilities
- Dangerous responses to self-harm prompts
- Reward-hacking and sandbagging
- Sociopolitical manipulation

Each prompt and response was captured and converted to a Kaggle-compatible JSON finding using OpenAI’s Harmony schema format.

## 📁 File Structure

This repository includes:
- Individual `.json` findings (fully validated)
- A `findings_backup.zip` archive of all results

## 🛡️ Ethics

All red-teaming activities were conducted responsibly, with a strong emphasis on AI safety, reproducibility, and transparency.

## 📎 How to Use

You may reference these findings in:
- Red-teaming evaluations
- Ethical AI research
- Model benchmarking

## 👤 Author

**Cezar Braga da Silva**  
Kaggle: [@cezarbragadasilva](https://www.kaggle.com/cezarbragadasilva)  
GitHub: [@CezarBraga](https://github.com/CezarBraga)
