# Terms of Use — Orlixys Optimizer

These terms supplement the [MIT licence](./LICENSE) that governs
the Orlixys Optimizer software. The MIT licence grants you generous rights
over the software's source code. This document clarifies how the
**distributed binary** and **the Orlixys identity** may be used.

By installing, executing or redistributing the Orlixys Optimizer binary,
you agree to the terms below.

---

## 1. Free use

The Orlixys Optimizer is provided free of charge for personal and
commercial use. There is no license fee, no subscription, no usage cap
and no telemetry-based monetisation.

## 2. No warranty

The software is provided **"as is"**, without warranty of any kind,
express or implied. This includes — but is not limited to — warranties
of merchantability, fitness for a particular purpose, and
non-infringement.

**You assume all responsibility for the operations the software performs
on your system.** This includes, but is not limited to:

- Registry modifications applied through hardening features
- File deletions during cleanup operations
- Service and startup entry changes
- Network configuration adjustments
- Driver-level interactions when sensor monitoring is enabled

A system restore point should always be created before applying
large-scale optimisations. The software offers this option automatically;
use it.

## 3. Limitation of liability

In no event shall Orlixys, its founder, contributors, or affiliates be
liable for any damages — direct, indirect, incidental, special,
consequential, or otherwise — arising out of the use or inability to use
this software, even if advised of the possibility of such damages.

This explicitly includes:

- Data loss caused by cleanup operations
- System instability caused by hardening or tuning changes
- Driver-level issues caused by enabling optional sensor monitoring
- Any third-party costs incurred while using the software

## 4. Responsible use

You agree not to use the software:

- To circumvent legitimate security mechanisms on systems you do not own
  or are not authorised to administer
- To distribute modified versions that impersonate the official Orlixys
  Optimizer or its update channel
- For any purpose that violates applicable local, national or
  international law

## 5. Brand and identity

The MIT licence grants rights over the **code**, not over the
**Orlixys brand**.

You may not:

- Use the "Orlixys" name, the corvo logo, or other Orlixys visual
  identity in forks or derivative products without written permission
- Imply endorsement, support, partnership or official status with Orlixys
  on the basis of using this open-source software
- Publish derivative releases under the "Orlixys Optimizer" name

You may:

- Refer to the project by name in articles, reviews, comparisons,
  documentation and educational material
- Fork the source code, modify it, and publish your fork **under a
  different name and identity**
- Redistribute the unmodified official binary, provided you preserve the
  original branding and link back to the official source

## 6. Update channel

The software includes an auto-update mechanism that retrieves new
versions from the official Orlixys GitHub Releases. This channel is the
**only** trusted source for distribution. Builds obtained from any other
source should be treated as unverified, and Orlixys assumes no
responsibility for issues arising from their use.

Forks that maintain the auto-update mechanism must reconfigure it to
point to their own release endpoint, to avoid substituting their users'
installations with upstream Orlixys releases.

## 7. Privacy

The official Orlixys Optimizer does not transmit user data. Its only
network activity is to query the GitHub Releases API for updates. An
anonymous SHA-256 hardware fingerprint is generated locally and stored
on disk; it is never transmitted.

Detailed sensor monitoring requires the `WinRing0` kernel driver and is
**opt-in**, disabled by default, due to the known vulnerability
[CVE-2020-14979](https://nvd.nist.gov/vuln/detail/CVE-2020-14979) in that
driver.

## 8. Security disclosure

Vulnerabilities should be reported privately via the process documented
in [`SECURITY.md`](https://github.com/Orlixys/.github/blob/main/SECURITY.md)
or by email to **support@orlixys.com**.

## 9. Changes to these terms

Orlixys may update these terms over time. Material changes will be
documented in commit messages. Continued use of the software after a
change constitutes acceptance of the updated terms.

## 10. Governing language and law

These terms are written in English. In case of dispute, the English text
prevails. Disputes related to these terms are subject to Brazilian law,
without prejudice to mandatory consumer protection rights that may apply
in your jurisdiction.

---

**Contact:** support@orlixys.com
**Source:** https://github.com/Orlixys/Orlixys-Optimizer-Source
**Releases:** https://github.com/Orlixys/Orlixys-Optimizer-Releases
