---
title: "When Time Disappears"
description: "What changes when payments become instant and the old safety buffer of delay disappears."
section: essay
sitemap: true
machine_readable: true
order: 60
date_published: 2026-04-03
last_modified: 2026-04-17
canonical_source: "https://theinvisiblemachine.eu/!test/article.php?slug=when-time-disappears&type=essay"
---

# When Time Disappears

Time almost always played an important role in payments. It was a kind of safety buffer.

Published: 2026-04-03

## What this essay is about

This essay examines what changes when payments become instant. It focuses on the loss of delay between initiation and final settlement, and on the consequences of that loss for verification, intervention, fraud prevention, and the practical meaning of authorisation.

## Why it matters

Time used to provide room for reconciliation, challenge, and correction. Instant payments remove much of that room. As a result, the system has to rely more heavily on checks and warnings placed before the payment is made, when the user still appears to be acting freely but the space for correction has already narrowed.

Time almost always played an important role in payments. The delay between payment initiation, clearing, and posting provided a margin for verification, reconciliation, and possible intervention. Errors could be detected before the transaction was finalised. Fraud could be stopped, and liability challenged.

Instant payments removed this margin. Funds are transferred to the payee’s account within a few seconds. Finalisation is immediate, and the transaction cannot be reversed through an ordinary process. This not only sped up payments but also shifted verification to the moment before initiation, before any result is known.

In payment architectures that are not instant, delays are inherent to the process. In card payments, the system balances the speed of authorisation with the possibility of chargeback and the dispute-resolution mechanism. Instant payments eliminate both of these factors. Verification therefore must take place before the transaction is carried out, not after.

In the euro area, instant payments were introduced through the SEPA Instant Credit Transfer (SCT Inst) scheme. SCT Inst allows euro transfers between bank accounts with settlement times of up to 10 seconds, available at any time, 365 days a year. Participation was formally voluntary at first, but the Instant Payment Regulation (2024) made the model effectively mandatory.

Despite almost full reachability of banks, instant payments did not become widespread immediately. This was connected to the cost of the requirements. Banks must maintain continuous liquidity, and anti-fraud checks and sanctions screening must be carried out without delay. This may be difficult especially for smaller institutions.

Low adoption was also caused by consumer fees, sometimes much higher than those for traditional transfers.

Thanks to regulatory action, the obligation to offer instant payments, and equalisation in price with regular transfers, the dominance of this type of transfer is only a matter of time.

In the case of instant payments, control mechanisms shift before transaction authorisation. In this context, verification of payee, also imposed on banks by the Instant Payment Regulation, gains particular importance.

Verification of payee checks whether the account number and the payee’s name in the transfer details match. Before the transfer is carried out, the payer’s bank makes an inquiry to the payee’s bank, and the response is shown to the customer. The transaction is not stopped even if a mismatch appears; everything depends on the customer’s decision. Verification of payee is intended above all to counter APP fraud.

In APP fraud, the victim is manipulated into making the transfer personally and authorising it properly. Because instant transfers post immediately, recovering the funds is often very difficult or impossible. Verification of payee can certainly thwart some frauds of this type.

It is not fully sufficient, however. It has weak points related to typos, special characters, or mistakes in names. It can also blur liability when the customer ignores information about a mismatch.

The transition to instant payments speeds up current processes and has a positive effect on many aspects of everyday life and the economy. It also means a significant and lasting change in the operation of the whole system: delay can no longer serve to detect errors or fraud. Prevention had to replace post-facto actions. The interface and the warnings shown to the user became important elements of managing this process.

## What follows from this

If the disappearance of delay moves control closer to the moment of action, the next question is who shapes that moment most directly. Wallets do exactly that, because they sit at the point where credentials, interfaces, and payment choices come together.

## Shared context

- [Dictionary]({{ site.baseurl }}/references/dictionary/)
- [Bibliography]({{ site.baseurl }}/references/bibliography/)
- [Regulations]({{ site.baseurl }}/references/regulations/)
- [Infrastructure, standards and schemes]({{ site.baseurl }}/references/infrastructure-standards-schemes/)
