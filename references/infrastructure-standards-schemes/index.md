---
title: "Infrastructure, standards and schemes"
description: "Shared map of systems, standards, schemes, networks, APIs, and wallet initiatives relevant to digital finance in Europe."
section: reference
sitemap: true
machine_readable: true
order: 104
last_modified: 2026-04-17
canonical_source: "https://theinvisiblemachine.eu/!test/infrastructure-standards-schemes.php"
---

# Infrastructure, standards and schemes

## Infrastructure systems

### TARGET Services
Umbrella term for the Eurosystem market infrastructure services for payments and securities. It anchors settlement and liquidity management within the euro area.  
Source: https://www.ecb.europa.eu/paym/target/html/index.en.html

### T2
The Eurosystem real-time gross settlement service for large-value payments in central bank money. It is the core settlement layer for euro payments and liquidity.  
Source: https://www.ecb.europa.eu/paym/target/html/index.en.html

### T2S
The Eurosystem platform for securities settlement in central bank money. It matters as part of the wider TARGET architecture and post-trade infrastructure.  
Source: https://www.ecb.europa.eu/paym/target/html/index.en.html

### TIPS
TARGET Instant Payment Settlement is the Eurosystem service for settling instant payments in central bank money around the clock.  
Source: https://www.ecb.europa.eu/paym/target/tips/html/index.en.html

### TARGET Shared Features / Common Components
Shared technical and operational components used across TARGET Services. They illustrate how common infrastructure is modularised and reused.  
Source: https://www.ecb.europa.eu/paym/target/coco/html/index.en.html

### RT1
A pan-European private-sector instant payment system operated by EBA CLEARING. It is a major operational rail for SCT Inst traffic.  
Source: https://www.eba-clearing.eu/

### Card payment acceptance terminals
Merchant acceptance devices for card payments. They matter as the visible edge of card infrastructure and scheme reach.  
Source: https://www.ecb.europa.eu/press/stats/paysec/html/index.en.html

## Standards

### ISO 20022
The universal financial industry messaging scheme used across many payment and financial-market infrastructures. It structures how financial data travels between systems.  
Source: https://www.iso20022.org/iso-20022

### ISO 20022 Message Catalogue
The public catalogue of ISO 20022 business messages. It is a practical reference for the message sets underpinning modern payment interoperability.  
Source: https://www.iso20022.org/catalogue-messages

### ISO 20022 Repository
The ISO 20022 repository containing message definitions and related artefacts. It is the canonical source for the standard’s technical content.  
Source: https://www.iso20022.org/financial-repository

### EMV Payment Tokenisation
EMVCo’s framework for replacing card primary account numbers with payment tokens. It is central to wallet-based card provisioning and credential control.  
Source: https://www.emvco.com/emv-technologies/payment-tokenisation/

### EMV 3-D Secure
An EMVCo protocol for additional authentication in remote card payments. It is one of the key standards at the intersection of card security and user experience.  
Source: https://www.emvco.com/emv-technologies/3-d-secure/

### EMV Secure Remote Commerce (SRC / Click to Pay baseline)
An EMVCo framework for standardised remote card checkout experiences. It matters where card credentials, wallets, and interface control converge.  
Source: https://www.emvco.com/emv-technologies/secure-remote-commerce/

### NFC Forum Specifications
The technical specifications maintained by the NFC Forum for near-field communication. They underpin contactless interaction between devices and payment instruments.  
Source: https://nfc-forum.org/build/specifications

### NFC Digital Protocol Technical Specification
The NFC Forum specification for digital protocol behaviour in NFC communication. It matters for contactless payment and wallet initiation.  
Source: https://nfc-forum.org/build/specifications/digital-protocol-technical-specification/

### NFC Analog Technical Specification
The NFC Forum specification covering analog characteristics of NFC communication. It forms part of the contactless device layer behind wallet and card interactions.  
Source: https://nfc-forum.org/build/specifications/analog-technical-specification/

### ETSI TC ESI
ETSI’s technical committee on electronic signatures and infrastructures. It is a major standards venue for eIDAS-related trust-service specifications.  
Source: https://www.etsi.org/committee/esi

### ETSI EN 319 401
A general-policy requirements standard for trust service providers supporting electronic signatures and related trust services.  
Source: https://www.etsi.org/deliver/etsi_en/319400_319499/319401/03.02.01_60/en_319401v030201p.pdf

### ETSI TS 119 461
An ETSI technical specification relevant to identity-proofing and trust-service implementation in the eIDAS environment.  
Source: https://www.etsi.org/deliver/etsi_ts/119400_119499/119461/02.01.01_60/ts_119461v020101p.pdf

### ISO/IEC 24760-1
An international framework standard for identity-management terminology and concepts. It is relevant to the identity layer and the formalisation of digital identity systems.  
Source: https://www.iso.org/standard/77582.html

## Schemes

### SEPA Credit Transfer (SCT)
The EPC rulebook for standard SEPA credit transfers in euro. It standardises account-to-account retail payments across SEPA.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/epc-payment-schemes/sepa-credit-transfer/sepa-credit-transfer-rulebook-and

### SEPA Instant Credit Transfer (SCT Inst)
The EPC rulebook for euro instant credit transfers. It compresses execution time and shifts control and fraud-management needs to the initiation phase.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/epc-payment-schemes/sepa-instant-credit-transfer/sepa-instant-credit-transfer-rulebook

### SEPA Direct Debit Core (SDD Core)
The EPC rulebook for standard SEPA direct debits. It harmonises pull-based euro payments across participating PSPs.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/epc-payment-schemes/sepa-direct-debit-core

### SEPA Direct Debit B2B (SDD B2B)
The EPC rulebook for business-to-business SEPA direct debits. It is relevant to mandate handling and inter-PSP debit infrastructure.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/epc-payment-schemes/sepa-direct-debit-business-business

### Verification of Payee (VOP / VoP)
An EPC scheme and API framework for pre-execution payee-data verification. It inserts a standardised control step before SCT and SCT Inst execution.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/other-schemes/verification-payee

### SEPA Request-to-Pay (SRTP)
An EPC framework for sending and receiving payment requests. It sits at the interface layer between messaging, initiation, and account-to-account payment flows.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/other-schemes/sepa-request-pay

### SEPA Payment Account Access (SPAA)
An EPC scheme framework intended to structure premium payment-account access and data-sharing services beyond minimum PSD2 access.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/other-schemes/sepa-payment-account-access

### One-Leg-Out Instant Credit Transfer (OCT Inst)
An EPC scheme for certain instant transfers involving one PSP outside SEPA. It matters where euro payment standardisation meets cross-border reach.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/epc-payment-schemes/one-leg-out-instant-credit-transfer

### giroAPI Scheme
A German scheme initiative for API-based payment-account access and value-added services. It is relevant to domestic open-finance orchestration.  
Source: https://die-dk.de/en/giroapi-scheme/

### Cartes Bancaires (CB)
The domestic French card scheme. It is a national example of card infrastructure embedded within broader European and international acceptance patterns.  
Source: https://www.cartes-bancaires.com/

### girocard
Germany’s domestic card payment scheme. It is relevant to national schemes with limited cross-border scope.  
Source: https://www.girocard.eu/english/

### Dankort
Denmark’s domestic card scheme. It illustrates national payment autonomy within a broader European retail-payment landscape.  
Source: https://dankort.dk/en-GB/privat

### BankAxept
Norway’s domestic card scheme. It is relevant as a national example of scheme governance and merchant acceptance.  
Source: https://bankaxept.no/en

### BANCOMAT
Italy’s domestic payment scheme brand. It spans card and wallet-related services in the national payments landscape.  
Source: https://bancomat.it/en

### Bancontact
Belgium’s domestic payment scheme. It illustrates local market structure within the broader European payments architecture.  
Source: https://www.bancontact.com/en

### iDEAL
The Dutch online account-to-account payment scheme. It is one of the clearest examples of a domestic payment method with strong e-commerce significance.  
Source: https://ideal.nl/en

## Networks

### VisaNet
Visa’s global transaction-processing network. It is a core private infrastructure layer for card payments and related data flows.  
Source: https://corporate.visa.com/en/about-visa/visanet.html

### Mastercard Network
Mastercard’s global transaction-processing network. It is part of the concentrated external infrastructure on which European retail payments depend.  
Source: https://www.mastercard.com/global/en/business/payments/consumer-payments/network-processing.html

### MULTIBANCO
Portugal’s domestic payments network and ATM ecosystem. It is relevant to how national infrastructure can bundle multiple payment functions.  
Source: https://www.multibanco.pt/

## Frameworks and implementation models

### Berlin Group
A European industry body known for API standardisation work in payments and open finance. It helps translate legal access rights into technical interface conventions.  
Source: https://www.berlin-group.org/

### Berlin Group NextGenPSD2
A voluntary API framework for implementing PSD2 access-to-account services. It standardises interface behaviour while leaving room for internal divergence.  
Source: https://www.berlin-group.org/nextgenpsd2-downloads

### STET PSD2 API
A PSD2 API specification maintained by STET. It is an alternative market framework for account information and payment initiation interfaces.  
Source: https://www.stet.eu/en/psd2/

### PolishAPI
A Polish API standardisation initiative for open banking. It shows how national communities operationalised PSD2-style access requirements.  
Source: https://polishapi.org/en/

### European Digital Identity Wallet Architecture and Reference Framework (ARF)
The reference architecture for the EU Digital Identity Wallet ecosystem. It translates legal and governance objectives into technical design patterns.  
Source: https://digital-strategy.ec.europa.eu/en/library/european-digital-identity-wallet-architecture-and-reference-framework

### EU Digital Identity Wallet Toolbox
A coordinated implementation package for the EUDI wallet ecosystem. It supports harmonised technical and governance preparation across Member States.  
Source: https://digital-strategy.ec.europa.eu/en/policies/eudi-wallet-toolbox

### The Berlin Group — Open Finance Framework
A voluntary industry framework for standardising data access and service initiation beyond payments. It extends open-banking logic toward broader financial-data interoperability.  
Source: https://www.berlin-group.org/open-finance.html

## Wallet initiatives and mobile solutions

### Wero
The wallet and account-to-account payment initiative of the European Payments Initiative. It represents a pan-European attempt to reduce dependence on global card and platform ecosystems.  
Source: https://epicompany.eu/

### BLIK
A Polish mobile payment scheme covering P2P, online, in-store, and ATM use cases. It is a major example of national wallet-style orchestration.  
Source: https://www.blik.com/en/

### Vipps MobilePay
A Nordic regional wallet and payments brand formed through consolidation. It illustrates consortium-led wallet governance and regional scale.  
Source: https://vippsmobilepay.com/about

### Bizum
A Spanish mobile payment solution focused on P2P and merchant payments. It is relevant to account-to-account mobile payment adoption.  
Source: https://bizum.com/es/en/

### Swish
A Swedish mobile payment system widely used for P2P and merchant transactions. It is a prominent example of mobile-centric domestic payments.  
Source: https://www.swish.nu/

### TWINT
A Swiss mobile payment system used for in-store, online, and peer-to-peer payments. It is relevant as a wallet-centric national ecosystem.  
Source: https://www.twint.ch/en/

### MB WAY
A Portuguese mobile payment and transfer service connected to the domestic payments ecosystem. It illustrates wallet-style orchestration in a national market.  
Source: https://www.mbway.pt/

### BANCOMAT Pay
An Italian mobile payment service associated with BANCOMAT. It sits at the interface layer between users and domestic payment rails.  
Source: https://bancomat.it/en

## Institutions and initiatives

### European Payments Initiative (EPI)
The industry initiative behind Wero and related European payment ambitions. It is relevant as a coordination vehicle for pan-European payment alternatives.  
Source: https://epicompany.eu/

## Reference sources

### SEPA Scheme Country List
Official EPC reference list of countries and territories participating in SEPA schemes. It is a practical boundary map for scheme applicability.  
Source: https://www.europeanpaymentscouncil.eu/document-library/other/epc-list-sepa-scheme-countries

### EPC Registers of Participants
Official participant registers for EPC schemes. They provide operational visibility into which PSPs adhere to which scheme rulebooks.  
Source: https://www.europeanpaymentscouncil.eu/what-we-do/be-involved/register-participants/registers-participants-sepa-payment-schemes

### ETSI Standards Search (eIDAS / EUDI related)
A practical entry point for ETSI standards relevant to eIDAS and the European Digital Identity Wallet ecosystem.  
Source: https://www.etsi.org/standards/standards-search?search=eIDAS

### European Digital Identity (EUDI) Regulation Overview
An official European Commission overview of the European Digital Identity framework. It provides policy context for the legal and technical wallet architecture.  
Source: https://digital-strategy.ec.europa.eu/en/policies/eudi-regulation

### EU Digital Identity Wallet Pilot Implementation
A European Commission overview of the pilot implementation work for EU Digital Identity Wallets. It links architecture, governance, and deployment practice.  
Source: https://digital-strategy.ec.europa.eu/en/policies/eudi-wallet-implementation

### EU Digital Identity Wallet Technical Specifications Hub
The official hub for technical specifications supporting EUDI wallet implementation. It is a practical source for the evolving technical stack.  
Source: https://ec.europa.eu/digital-building-blocks/sites/spaces/EUDIGITALIDENTITYWALLET/pages/869793973/Technical+Specifications

### Commission Implementing Regulation (EU) 2025/846
An implementing act within the European Digital Identity Wallet framework. It is part of the secondary-rule layer that makes the identity architecture operational.  
Source: https://eur-lex.europa.eu/eli/reg_impl/2025/846/oj/eng

### Commission Implementing Regulation (EU) 2025/848
An implementing act within the European Digital Identity Wallet framework. It contributes to the operational rule layer of the wallet ecosystem.  
Source: https://eur-lex.europa.eu/eli/reg_impl/2025/848/oj/eng

### Commission Implementing Regulation (EU) 2025/849
An implementing act within the European Digital Identity Wallet framework. It is relevant as part of the detailed operationalisation of eIDAS 2.0.  
Source: https://eur-lex.europa.eu/eli/reg_impl/2025/849/oj/eng

### Commission Implementing Regulation (EU) 2025/1569
An implementing act within the European Digital Identity Wallet framework. It forms part of the secondary legal layer around wallet deployment.  
Source: https://eur-lex.europa.eu/eli/reg_impl/2025/1569/oj/eng

### EWC (EU Digital Identity Wallet Consortium)
One of the large-scale pilot consortia testing EU Digital Identity Wallet use cases. It connects policy ambitions with practical implementation.  
Source: https://www.digital-identity-wallet.eu/

### POTENTIAL
A large-scale pilot project for EU Digital Identity Wallet use cases. It is part of the experimentation layer for the EUDI ecosystem.  
Source: https://www.potentialproject.eu/
