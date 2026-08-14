# Security Policy

## Supported Versions

StarC is under active development. Below are the versions currently supported with security updates:

| Version | Supported | Platform |
| ------- | --------- | -------- |
| v0.1.x  | :white_check_mark: | Windows 10/11 (MSYS2), Linux (Ubuntu 20.04+) |
| v0.0.x  | :x: | Development only, not recommended for production |

### Platform Support Details

| Platform | Architecture | Status | Notes |
| -------- | ------------ | ------ | ----- |
| Windows 10/11 (MSYS2) | x86_64 | :white_check_mark: | Fully supported with GCC/MinGW |
| Windows 7/8 | x86_64 | :warning: | Compatible but not fully tested |
| Linux (Ubuntu 20.04+) | x86_64 | :white_check_mark: | Fully supported with GCC |
| Linux (Other distros) | x86_64 | :warning: | Compatible with glibc 2.31+ |
| macOS | x86_64 / ARM64 | :x: | Planned for future releases |
| ARM64 (Linux) | ARM64 | :x: | Planned for future releases |

> **Compiler Requirement:** GCC 10.0+ or Clang 14.0+
>
> **Runtime Library:** `libstar_runtime` v0.1.x (70+ modules)

---

## Reporting a Vulnerability

We take security seriously at StarC. If you discover a security vulnerability, please follow these steps:

### How to Report

1. **Do NOT** open a public issue on GitHub.
2. Send an email to: **8010456@qq.com**
3. Include the following information:
   - A clear description of the vulnerability
   - Steps to reproduce the issue
   - The version of StarC you are using
   - Your operating system and compiler version
   - Any relevant logs or code snippets

### What to Expect

| Response Time | Action |
| -------------- | ------ |
| Within 24 hours | Acknowledgment of your report |
| Within 3-5 days | Initial assessment and severity classification |
| Within 7-14 days | Fix or mitigation plan (if accepted) |
| After fix | Public disclosure with credit to the reporter |

### Responsible Disclosure

- We follow a **90-day responsible disclosure** timeline.
- If the vulnerability is accepted, we will work with you to coordinate the disclosure.
- If the vulnerability is declined, we will provide a clear explanation.
- We will publicly credit reporters unless they wish to remain anonymous.

---

## Security Best Practices for StarC Users

1. **Always use the latest version** of StarC for security-critical projects.
2. **Verify checksums** before using third-party StarC modules.
3. **Run StarC in a sandboxed environment** when processing untrusted input.
4. **Report any suspicious behavior** immediately using the contact above.

---

## Past Security Advisories

| Advisory ID | Date | Affected Versions | Description | Status |
| ----------- | ---- | ----------------- | ----------- | ------ |
| None yet | — | — | No security advisories published | — |

---

## Contact

- **Security Email:** 8010456@qq.com
- **GitHub Security Advisory:** [GitHub Security](https://github.com/8010456-wq/starc/security/advisories)
- **Emergency Contact:** *(optional)*

---

**Last Updated:** 2026-08-14
