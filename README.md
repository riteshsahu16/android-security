# android-security

## 1. Application Components

1. **components/**

   1. `activities/`
   2. `services/`
   3. `broadcast-receivers/`
   4. `content-providers/`
   5. `exported-components/`

2. **ipc-and-intents/**

   1. `intent-security/`
   2. `intent-redirection/`
   3. `pending-intents/`

---

## 2. Authentication & Authorization

1. **authentication/**

   1. `authentication/`
   2. `biometric-auth/`
   3. `permissions/`
   4. `privilege-escalation/`

2. **authorization/**

   1. `component-permissions/`
   2. `custom-permissions/`
   3. `runtime-permissions/`

---

## 3. Data & Local Storage Security

1. **data-storage/**

   1. `insecure-storage/`
   2. `shared-preferences/`
   3. `sqlite-databases/`
   4. `files/`
   5. `external-storage/`

2. **data-leakage/**

   1. `insecure-logging/`
   2. `clipboard/`
   3. `screenshots/`
   4. `backup/`

---

## 4. Cryptography & Key Management

1. **cryptography/**

   1. `weak-algorithms/`
   2. `weak-randomness/`
   3. `hardcoded-keys/`
   4. `improper-cryptography/`

2. **key-management/**

   1. `keystore/`
   2. `key-generation/`
   3. `key-storage/`
   4. `key-management/`

---

## 5. Network & API Security

1. **network-security/**

   1. `network-security-config/`
   2. `ssl-pinning/`
   3. `tls/`
   4. `certificate-validation/`
   5. `cleartext-traffic/`

2. **api-security/**

   1. `api-authentication/`
   2. `api-authorization/`
   3. `api-endpoints/`
   4. `api-secrets/`
   5. `api-misconfiguration/`

---

## 6. Web & WebView Security

1. **webviews/**

   1. `javascript-interface/`
   2. `javascript-enabled/`
   3. `file-access/`
   4. `url-loading/`
   5. `webview-configuration/`
   6. `webview-xss/`

2. **deep-links/**

   1. `custom-schemes/`
   2. `app-links/`
   3. `universal-links/`
   4. `deep-link-validation/`
   5. `intent-injection/`

---

## 7. Application Hardening

1. **debugging/**

   1. `debuggable/`
   2. `debug-interfaces/`
   3. `development-configurations/`

2. **root-detection/**
   3. `root-detection/`
   4. `environment-detection/`
   5. `integrity-checks/`

3. **application-integrity/**

   1. `signature-validation/`
   2. `tamper-detection/`
   3. `repackaging/`
   4. `runtime-integrity/`

---

## 8. Android Platform Security

1. **platform-security/**

   1. `sandbox/`
   2. `uid-isolation/`
   3. `binder-ipc/`
   4. `selinux/`
   5. `filesystem-permissions/`

2. **system-services/**

   1. `system-service-abuse/`
   2. `binder-security/`
   3. `privileged-apis/`

---

## 9. Testing & Analysis

1. **static-analysis/**

   1. `manifest-analysis/`
   2. `code-analysis/`
   3. `dependency-analysis/`
   4. `secrets-analysis/`

2. **dynamic-analysis/**

   1. `runtime-analysis/`
   2. `instrumentation/`
   3. `traffic-analysis/`
   4. `behavior-analysis/`

3. **vulnerability-testing/**

   1. `component-testing/`
   2. `ipc-testing/`
   3. `webview-testing/`
   4. `api-testing/`
   5. `storage-testing/`

---

## 10. Findings & Exploitation Classes

1. **common-vulnerabilities/**

   1. `exported-components/`
   2. `intent-injection/`
   3. `path-traversal/`
   4. `insecure-data-storage/`
   5. `insecure-communication/`
   6. `authentication-bypass/`
   7. `authorization-bypass/`
   8. `information-disclosure/`

2. **writeups/**

   1. `case-studies/`
   2. `ctfs/`
   3. `vulnerable-apps/`
   4. `bug-bounty/`

---

## 11. Tooling

1. **tools/**

   1. `jadx/`
   2. `apktool/`
   3. `adb/`
   4. `frida/`
   5. `objection/`
   6. `drozer/`
   7. `mitmproxy/`
   8. `burp-suite/`
   9. `ghidra/`

2. **scripts/**

   1. `static-analysis/`
   2. `dynamic-analysis/`
   3. `frida-scripts/`
   4. `apk-scripts/`
   5. `automation/`


## Each concept could follow:
Concept
↓
Why it matters
↓
Vulnerable implementation
↓
Exploitation scenario
↓
Testing methodology
↓
Impact
↓
Secure implementation
