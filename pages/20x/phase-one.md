---
layout: leftnav-rightlink
title: FedRAMP 20x - Phase One
tab-title: FedRAMP 20x - Phase One
permalink: /20x/phase-one/
body-class: page-training
navigation:
  - id: phase1goal
    title: Phase 1 Goal
  - id: phase1eligibility
    title: Phase 1 Eligibility
  - id: howitworks
    title: How it will work
  - id: agencies
    title: How it helps agencies
---

## Phase 1 Goal {#phase1goal}

A cloud-native continuous security assessment that’s as simple as your cloud
service offering - or as complex as needed. Meet federal security requirements
and get authorized in weeks.

- No more unnecessary or duplicative paperwork; bring your existing security
  certifications
- Quick and easy compliance for simple environments; click and go
- Automated continuous assessment by widely available commercial tools; improve
  your products without asking for permission
- Requirements that are easy to understand, flexible, and easy to implement;
  just show them to your engineers
- Make your own business decisions about what to implement; federal agency
  customers make their own choices based on your decisions
- No agency sponsor required; just secure your systems and get ready
- FedRAMP High will initially stay with the current manual process, but will
  benefit from continuous automation improvements until it is covered under the
  new process in following phases

## Phase 1 Eligibility {#phase1eligibility}

FedRAMP 20x reimagines security assessment for cloud service offerings, starting
with the simplest of environments where security can be built in with a few
simple changes. It will grow to include additional use cases until all modern
cloud services are covered.

For Phase 1, Software-as-a-Service offerings that meet the following
requirements are eligible:

- Deployed on an existing FedRAMP Authorized cloud service offering using
  entirely or primarily cloud-native services
- Minimal or no third party cloud interconnections; all services handling
  federal information must be FedRAMP Authorized
- Service is provided only via the web (browser and/or APIs)
- Offering supports a few standard customer configured features needed by
  federal agencies (or you’re willing to build that capability quickly)
- Existing adoption of commercial security frameworks are a plus (SOC 2, ISO
  27000, CIS Controls, HITRUST, etc.)

_Full details on eligibility requirements to be added during development. Phase
2+ will expand eligibility based on the success of Phase 1._

## How It Will Work {#howitworks}

FedRAMP 20x broadly groups security requirements into two categories,
**Documentation** and **Automated Validations.**

**Documentation** requirements expect companies to write down their business
processes and explain how they follow them to keep federal information safe.

- Review the documentation requirements and determine which controls you are
  willing to meet and how you will meet them. You can make your own or just
  accept the specific requirements provided by FedRAMP.
- If you use an existing commercial security framework, you will provide those
  materials where they overlap with FedRAMP’s documentation requirements.
- For Example: The Security & Privacy Policy requirement calls for documenting a
  business process to provide role-based training to staff on security
  practices. To produce evidence of this requirement, you may either:
  - Include your current policy on employee security training
  - Accept and implement FedRAMP’s or CISA’s guidance on training expectations
  - Include existing commercial security assessment materials that demonstrate
    relevant staff education and training processes

**Automated Validations** includes requirements and expectations for either the
host infrastructure or a compliance service can provide automated technical
validations that the infrastructure is configured securely. Configurations can
be automatically reviewed continuously or even directly enforced by the host
infrastructure.

- Review the technical requirements and determine which you are willing to meet.
- Make the configuration changes necessary to meet these controls.
- Configure the host infrastructure provider or compliance service to
  continuously monitor and / or enforce the status of your configuration.
- For Example: Encryption requirements call for all systems storing federal
  information to encrypt that information. In response to this control you
  might:
  - Configure encryption at rest on all storage services that may handle federal
    information
  - Create a configuration enforcement policy to prevent deployment of
    non-encrypted storage services
  - Configure an enforcing system to continually enforce encryption on all
    storage services

The output from a FedRAMP 20x assessment process includes materials produced for
the Documentation requirements and output from the initial execution of
Automated Validations. Continuous monitoring is performed by ensuring the
process used for implementing automated validations is executed continuously and
any deviations are addressed in a timely manner.

After an assessment is completed, the cloud service offering will receive a
score with a focus on the areas of Confidentiality, Integrity, and Availability
of federal information. Agencies will review this information to compare vendors
to make risk assessments of the cloud service prior to adoption.

## How It Helps Agencies {#agencies}

Agencies will be able to rapidly adopt cloud services and make informed
decisions based on their confidentiality, integrity, and availability needs via
a comparison tool that allows them to rapidly match with the services that meet
their security expectations. Instead of re-using FedRAMP authorizations made by
other agency sponsors, agency teams will be able to ATO cloud services that meet
FedRAMP 20x requirements in days.
