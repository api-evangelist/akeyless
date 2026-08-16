---
title: "Jenkins Secrets, Explained: What the Credentials Plugin Gets Wrong"
url: "https://www.akeyless.io/blog/jenkins-secrets/"
date: "2026-08-14"
author: "Anshika Sharma"
feed_url: "https://www.akeyless.io/blog/feed/"
---
Key Takeaways Jenkins’ Credentials Plugin encrypts secrets at rest, but the design is decryptable: anyone with Script Console access can run Groovy code to decrypt any stored credential, and the master key that protects everything else sits unencrypted on the filesystem. The native plugin also has no automated rotation, no audit trail of who accessed […] The post Jenkins Secrets, Explained: What the Credentials Plugin Gets Wrong appeared first on Akeyless .
