# Notes — AWS Cloud Practitioner Essentials (AWS Skill Builder)

Module by module, same format as the cisco notes. 13 modules here, no labs, so these are more concept focused then my usual notes with commands/labs mixed in.

---

## Module 1 — Introduction to the Cloud

Basics of what cloud computing actually is, on demand access to compute resources instead of owning physical hardware yourself. Covers the shift from traditional on-prem infrastructure to cloud, and why that shift actually happened (cost, scalability, not having to manage physical servers yourself).

---

## Module 2 — Compute in the Cloud

Compute basics — EC2 specifically, virtual servers you can spin up and down as needed. Covers instance types, and the general idea of paying for what you use instead of buying fixed hardware upfront.

---

## Module 3 — Exploring Compute Services

Goes deeper into compute options beyond just basic EC2 — different services for different use cases (containers, serverless stuff like Lambda). Comparing when you'd actually pick one over another instead of just knowing they exist.

---

## Module 4 — Going Global

Regions and availability zones — how AWS infrastructure is physically spread out globally, and why that matters for both latency (put your stuff close to your users) and redundancy (spread across zones so one outage doesn't take everything down).

---

## Module 5 — Networking

VPCs, subnets, basic networking within AWS specifically. This one took more effort then the others honestly — i already know subnetting and VPC-adjacent concepts from the cisco networking courses, but AWS's specific terminology and how it maps onto that existing knowledge wasnt 1:1 obvious right away. Had to slow down and actually connect the dots instead of assuming it'd just click automatically.

---

## Module 6 — Storage

S3 mainly, plus other storage options (EBS, etc). Object storage vs block storage distinction, and when you'd use each.

---

## Module 7 — Databases

Managed database services — RDS and similar. The idea of AWS handling the database administration overhead (patching, backups) instead of you managing it all yourself on a self hosted DB.

---

## Module 8 — AI ML and Data Analytics

Lighter module, more of a survey of what exists (SageMaker etc) then anything hands on. Good to know these services exist even if i'm not using them right now.

---

## Module 9 — Security

Probably the module i got the most out of given my SOC background already. The shared responsibility model specifically stuck with me — AWS is responsible for security OF the cloud (the actual infrastructure), you're responsible for security IN the cloud (how you configure what you put there). Simple framing but it reframed a bunch of stuff i already knew about defense in depth from cisco courses, just applied to cloud context instead of general networking.

IAM also covered here — identity and access management, least privilege access basically applied to AWS specifically.

---

## Module 10 — Monitoring, Compliance and Governance in the AWS Cloud

CloudWatch and similar monitoring tools, plus compliance/governance concepts — making sure cloud usage actually follows whatever regulatory or internal policy requirements apply.

---

## Module 11 — Pricing and Support

Almost skipped this mentally expecting it to be dry, but its genuinely useful. How AWS billing actually works, the different pricing models (on-demand, reserved, spot), and the different support tiers available. This is the kind of thing that matters practically once your actually using AWS for real, not just conceptually understanding services.

---

## Module 12 — Migrating to the AWS Cloud

Strategies for actually moving existing infrastructure into AWS — different approaches depending on how much you want to change vs just lift-and-shift what already exists.

---

## Module 13 — Well-Architected Solutions

The AWS Well-Architected Framework — a set of best practice pillars (things like operational excellence, security, reliability, cost optimization) for designing cloud systems properly instead of just making something that technically works.

---

## Overall

Good first step into cloud specifically because it built the vocabulary before i went into anything deeper. Security module connected the most directly to what i already knew from SOC training — the shared responsibility model specifically is a genuinely useful mental model. Networking module needed the most active effort since the terminology didnt map onto cisco knowledge as automatically as id expected.

No labs in this course so nothing hands on yet — thats the next phase, starting with FreeCodeCamp's deeper course then actual Free Tier projects.
