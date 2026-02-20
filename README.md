# Hello there 👋

(But where's the `higher ground` XD)

## 🥔 About Me

- IIT Kharagpur '24
- Systems + infrastructure engineer focused on **operating systems, distributed systems, and cloud-native internals**
- Active open-source contributor to **etcd, kernel-adjacent runtimes, and low-level tooling**
- I document projects and experiments here: https://sneaky-potato.github.io/

---

## Contributions to Open Source

I like to give back to community and help other codebases in whatever capacity I can in my free time.

**[Etcd](https://etcd.io/) - Distributed Key-Value Store (CNCF)**

Contributions across robustness testing, authentication, client behavior, and server internals:

- Improved client-server authentication for client managed JWTs [#20747](https://github.com/etcd-io/etcd/pull/20747), [#20802](https://github.com/etcd-io/etcd/pull/20802)
- Removed duplicate delete/compact operations in robustness tests, reducing linearization cost [#20877](https://github.com/etcd-io/etcd/pull/20877), [#21043](https://github.com/etcd-io/etcd/pull/21043)

**[Lua In Kernel](http://www.lua.inf.puc-rio.br) - Kernel Adjacent Runtime**

- Eliminated index-based method dispatch by eagerly wrapping class methods at initialization, reducing allocations in hot paths [#410](https://github.com/luainkernel/lunatik/pull/410)
- Added LLDP example using `AF_PACKET` to demonstrate low-level packet I/O [#341](https://github.com/luainkernel/lunatik/pull/341)
- Standardized raw socket patterns for safer reuse [#360](https://github.com/luainkernel/lunatik/pull/360), [#364](https://github.com/luainkernel/lunatik/pull/364)
- Enforced explicit (protocol, ifindex) pairing in raw socket `bind()` for API correctness [#378](https://github.com/luainkernel/lunatik/pull/378)

**[Trivy](https://trivy.dev/latest/)**

- Fixed Java dependency analysis by excluding development dependencies from Gradle lockfile [#8803](https://github.com/aquasecurity/trivy/pull/8803)
- Updated documentation to clarify handling of development dependencies in Gradle lockfiles [#8830](https://github.com/aquasecurity/trivy/pull/8830)
- Added support for parsing `bun.lock` files to improve Node.js ecosystem coverage [#8851](https://github.com/aquasecurity/trivy/pull/8851)
- Implemented vulnerability analysis for Bun lockfiles in Node.js projects [#8897](https://github.com/aquasecurity/trivy/pull/8897)

**[Rust-GCC](https://rust-gcc.github.io/)**
- _Check for deprecated attributes_ -- [Commit Link](https://github.com/Rust-GCC/gccrs/commit/d74c8b4692568bbfc647ef13ac46050d0a53b0f2) / [PR Link](https://github.com/Rust-GCC/gccrs/pull/4327)

---

## 🗃️ Weekly stats

I like to track my time, [Wakatime](http://wakatime.com/) and this awesome [action](https://github.com/athul/waka-readme) allows me to
do that automatically.


<!--START_SECTION:waka-->

```txt
From: 12 February 2026 - To: 19 February 2026

C               7 hrs 7 mins          ████████████████░░░░░░░░░   63.92 %
C++             2 hrs 22 mins         █████▒░░░░░░░░░░░░░░░░░░░   21.25 %
Markdown        58 mins               ██▒░░░░░░░░░░░░░░░░░░░░░░   08.82 %
Makefile        17 mins               ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.55 %
Git             11 mins               ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.67 %
```

<!--END_SECTION:waka-->

---

## 🤝 Connect

[![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashwani-k-kamal/)

---

## ❇️ Vamos Muchachoes

<img align = "right" height = "130" width = "130" src="https://media.giphy.com/media/LwHaQCGZMdD9Ghalrl/giphy.gif">

Counter for something something:

[![wakatime](https://wakatime.com/badge/user/e0871c9e-5a07-4036-9354-41563cad914d.svg)](https://wakatime.com/@e0871c9e-5a07-4036-9354-41563cad914d)

![1x-engg](https://img.shields.io/github/stars/cutenode/1x.engineer.svg?color=purple&label=1x%20Engineers&logo=image%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAADAElEQVRoQ%2B1YPZMNQRQ9RyYiUCVkI0J%2BASUi4xfYzYjsVsmXX2BFZFauigyJ4hcQEtkNVQmoEjvqqh7VM6%2B%2FZ%2BapqXodvtdz%2B56%2B59zT3cTCBxeePzYA%2FncFNxUoqYCkEwC2AbwjeVTyTemctVRA0iUAH11SxwBekLxfmmRq3roA3AHwxEvkLcnrSwJwCOC2l%2FBDkg%2BWBOAzgAtewjdIvlkEAElnAHwDYEK28RvAWZLflwLAuP7aS%2FYLyYtTJG8xZhexJOP6vpfwc5LWUicZ6wDwHsAVL9u7JJ9Okv2YCki6SfJVKhFnYL8AnPTmXSb5yf%2BuJFZsnaYKSHoEYBfAIcmdWPCBgdk0E64J2IT8d0h65lz6gORebWWqAEg6DeAlgKveQjskrc%2BvDElJA5NkWjAA3TC63SL5oxRIMQC3m5b8%2BUHwn%2FZbaFFJUQNzm2HnolODePabgejRbBSF3E4ZbawC%2FrBzjWkhuJikpIG5TTEdnRvEtQrsxSrrz81WwOP7cBM%2BuOSD5S41MFcJA%2BF3qm6trC6iACJ87wI%2FJmkijg5JVQYm6QDAvUDApC6CADJ83y0pbYuBOaoakGJdrACwnuw6QxXfhzsnqcnAMrqwjtfznhCAr4FOk%2BR7IHk7uGUNLMa%2FhC6OSG4lRSzJ2tiwK1T15xIDy%2Bgn5Df2yTHJXhuPUcj6dzEPAxVovoFl9LedpZAlM7Y%2Fpwwss%2FPmzFV%2Bk2ujTf05Z2AhEK1%2BU2JkVf251MA6EGP9JgvAUcpKW9SfawxsCr8pAlCgi63uMFdqYG7nrWWP8ptiAA6ELTbURe84XWNggeN0ld9YTlUAPN52uujdb0tvYL6IvY6VPV%2BFxN8EwFVj5UrZamBrv1ImjgDNBpbyh9R%2FzRWI9PLZnhBjIKYGMNsT4uwAag2slTLD7yarQI2BTZV8cxuN8H%2FWJ8R1UKjpBja2GlNSyMzNrqPdZWjlCXFsspMaWcIL7MZ0zT07%2FntCnCP5STUwV4K5uJNRKLfQXP9vAMy1s6VxF1%2BBPxWSokDSvlDHAAAAAElFTkSuQmCC&?style=flat&logo=appveyor&link=https://1x.engineer&link=https://github.com/cutenode/1x.engineer/stargazers)

