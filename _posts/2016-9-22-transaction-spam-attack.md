---
layout: post
title: Transaction Spam Attack
tags: [vulnerability, gasprice]
---

Because `EXTCODESIZE` has a low gasprice but heavy IO cost, when attack transactions are calling this opcode many times perblock, the network is greatly slowing down, but there is no consensus failure or memory overload, which cause a computational DDoS attack.
