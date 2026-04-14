# Hello there 👋

(But where's the `higher ground` XD)

## About Me

- IIT Kharagpur 2024
- Systems and infrastructure engineer focused on **operating systems, distributed systems, and kernel/cloud-native internals**
- Active open-source contributor to **etcd, kernel-adjacent runtimes, and low-level tooling**
- Technical notes and experiments: https://sneaky-potato.github.io/

---

## Engineering philosophy

I focus on:
- Correctness under failure
- Removing unnecessary work from common paths
- API discipline at system boundaries (kernel/userspace, client/server)
- Runtime abstraction design

---

## Currently exploring

- eBPF runtime layers
- TC/XDP classifier design
- Scriptable networking paths

## Contributions to Open Source

**[Lua In Kernel](http://www.lua.inf.puc-rio.br) - Kernel Adjacent Lua Runtime**

- Added support for non-shared objects within shared classes, bypassing unnecessary object locking [#434](https://github.com/luainkernel/lunatik/pull/434)
- Eliminated index-based method dispatch by eagerly wrapping class methods at initialization, reducing allocations in hot paths [#410](https://github.com/luainkernel/lunatik/pull/410)
- Added LLDP example using `AF_PACKET` to demonstrate low-level packet I/O [#341](https://github.com/luainkernel/lunatik/pull/341)
- Standardized raw socket patterns for safer reuse [#360](https://github.com/luainkernel/lunatik/pull/360), [#364](https://github.com/luainkernel/lunatik/pull/364)
- Enforced explicit (protocol, ifindex) pairing in raw socket `bind()` for API correctness [#378](https://github.com/luainkernel/lunatik/pull/378)

**[Etcd](https://etcd.io/) - Distributed Key-Value Store (CNCF)**

Contributions across robustness testing, authentication, client behavior, and server internals:

- Improved client-server authentication for client managed JWTs [#20747](https://github.com/etcd-io/etcd/pull/20747), [#20802](https://github.com/etcd-io/etcd/pull/20802)
- Removed duplicate delete/compact operations in robustness tests, reducing linearization cost [#20877](https://github.com/etcd-io/etcd/pull/20877), [#21043](https://github.com/etcd-io/etcd/pull/21043)

**[Trivy](https://trivy.dev/latest/) - Security Scanner**

- Fixed Java dependency analysis by excluding development dependencies from Gradle lockfile [#8803](https://github.com/aquasecurity/trivy/pull/8803)
- Updated documentation to clarify handling of development dependencies in Gradle lockfiles [#8830](https://github.com/aquasecurity/trivy/pull/8830)
- Added support for parsing `bun.lock` files to improve Node.js ecosystem coverage [#8851](https://github.com/aquasecurity/trivy/pull/8851)
- Implemented vulnerability analysis for Bun lockfiles in Node.js projects [#8897](https://github.com/aquasecurity/trivy/pull/8897)

**[Rust-GCC](https://rust-gcc.github.io/) Rust Frontend by GCC**
- Check for deprecated attributes [#432](https://github.com/Rust-GCC/gccrs/pull/4327)

---

## 🗃️ Weekly stats

I like to track my time, [Wakatime](http://wakatime.com/) and this awesome [action](https://github.com/athul/waka-readme) allows me to
do that automatically.


<!--START_SECTION:waka-->

```txt
From: 06 April 2026 - To: 13 April 2026

Markdown   2 hrs 21 mins         ███████████████▓░░░░░░░░░   62.30 %
C++        59 mins               ██████▓░░░░░░░░░░░░░░░░░░   26.34 %
Typst      15 mins               █▓░░░░░░░░░░░░░░░░░░░░░░░   06.67 %
Lua        4 mins                ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.08 %
C          4 mins                ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.80 %
```

<!--END_SECTION:waka-->

---

