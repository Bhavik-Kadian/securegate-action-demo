# securegate-action-demo

A scratch repository where [SecureGate's GitHub Action](https://github.com/Bhavik-Kadian/Nexora/blob/main/docs/install.md) was tried on real pull requests, during the close-out of SecureGate v1.0.0 (Team Nexora, Microsoft Innovate 2026, Problem Statement 24).

- `.github/workflows/secret-gate.yml` is the workflow from "Protect any repository", unchanged apart from the version it uses.
- This repository has no `policy.yaml`, so SecureGate's own policy decides.
- The pull requests with a fake ACME Pay token (made by `securegate demo-token`) were closed, never merged. ACME Pay is a payment provider invented for SecureGate's demos: its tokens unlock nothing.
