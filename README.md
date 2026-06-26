# AI Security & Governance Studio

This repository contains the target configuration and SRE runtime files compiled by the **AI Security & Governance Studio** dashboard module.

## 🚀 Description
Configure prompt injection shields and SRE governance boundaries. Generate input/output safety classifiers and semantic access control guards.

## 🛠️ Specification Matrix
- **Primary Configuration File**: `/deploy/security/security_rules.yaml`
- **Execution Command**: `kubectl apply -f security_rules.yaml`
- **Validation Command**: `kubectl get safety-policies`

## 📋 How to Run & Validate

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pradeeptalari14/tp-ai-security.git
   cd tp-ai-security
   ```

2. **Run Execution Target:**
   ```bash
   kubectl apply -f security_rules.yaml
   ```

3. **Verify Runtime Stability:**
   ```bash
   kubectl get safety-policies
   ```

## 🔐 Security & Best Practices
* **Secret Isolation**: Use organization-level secrets (or SSM parameter hooks) rather than hardcoded environment variables inside files.
* **Pull Request Lifecycles**: Protect default branch merges with validation checks before merging code changes.
