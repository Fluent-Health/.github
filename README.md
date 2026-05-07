<p align="center">
  <img src="https://fluentinhealth.com/logo.png" alt="Fluent Health" height="64" />
</p>

<h1 align="center">Fluent Health</h1>

<p align="center">
  <i>Your health is too important to be everywhere.</i>
</p>

<p align="center">
  <a href="https://fluentinhealth.com">Website</a> •
  <a href="https://fluentinhealth.com/about">About</a> •
  <a href="https://www.linkedin.com/company/fluent-health">LinkedIn</a> •
  <a href="https://play.google.com/store/apps/details?id=com.fluenthealth.app&hl=en_IN">Google Play</a> •
  <a href="https://apps.apple.com/us/app/fluent-health/id1670153153">App Store</a>
</p>

---

## Why we exist

Health records sit scattered across hospitals, clinics, labs, apps, and inboxes. Every appointment starts from scratch. Every new doctor reads the same story you've already told a dozen times.

Fluent puts your health story in one place — a continuous timeline you actually own — so you never have to start over, repeat yourself, or lose what matters.

## How we build

Health software has to be three things at once: clear for the person using it, rigorous for the clinicians it serves, and secure by default — because health data isn't ordinary data.

That shapes our engineering:

- **FHIR-native, cloud-agnostic.** Every service speaks the standard. Every component runs on infrastructure we can move.
- **Defence-in-depth, end-to-end.** Zero-trust access between services, mutual TLS on the wire, encryption at rest with hardware-backed keys, short-lived credentials, signed and attested build artifacts. Security is the floor, not a feature.
- **Generative AI at the core.** Healthcare runs on a tidal wave of documents — handwritten prescriptions, scanned reports, consult notes across a dozen languages, each in its own bespoke format. Our generative models tame that complexity and turn it into structured, queryable health data you actually own.
- **Humans validate, not just review.** Every piece of clinical data is checked against source for correctness before it lands on a timeline. No inference passes as fact.
- **Designed for India, ready for the world.** DPDPA-aligned, ABDM-interoperable, with controls mapped to ISO 27001 and SOC 2 Type II.

## Open source at Fluent

Some of our stack is product. Some of it is plumbing. We open the plumbing — the pieces other teams shouldn't have to rebuild from scratch.

### Latest

**[gravitee-reporter-prometheus](https://github.com/Fluent-Health/gravitee-reporter-prometheus)**
A Prometheus reporter plugin for the Gravitee API Gateway. Drop it into your gateway, point Prometheus at it, and run Gravitee inside a Kubernetes-native observability stack without writing the glue yourself.

More repositories will follow as we extract them.

## How we work

- We ship behind release trains and signed images — every artifact is attested before it touches production.
- We measure what matters: latency, error rate, audit completeness, and whether a real person could find their report when they needed it.
- We document so the next engineer (or the next auditor) doesn't have to guess.

## Get in touch

If you're building in health tech, working on FHIR, or curious about what we do — say hi.

- Web: [fluentinhealth.com](https://fluentinhealth.com)
- Email: hello@fluentinhealth.com

---

<p align="center">
  <i>You show up for your health. We show up for what slows you down.</i>
</p>
