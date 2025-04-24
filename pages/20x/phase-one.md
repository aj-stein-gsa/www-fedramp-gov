---
layout: leftnav-rightlink
title: FedRAMP 20x - Phase One
tab-title: FedRAMP 20x - Phase One
permalink: /20x/phase-one/
body-class: page-training
navigation:
  - id: pilot
    title: Phase One Pilot
  - id: who
    title: Who Should Participate?
  - id: how
    title: How to Participate
  - id: example
    title: Example Participant Experience
---

# FedRAMP 20x Phase One Pilot {#pilot}

The FedRAMP 20x Phase One pilot tests how cloud service providers can meet FedRAMP Low authorization requirements using a combination of automated technical validation, existing commercial certification, and simple documentation requirements to generate machine-readable packages that can be assessed by trusted third parties. 

At the end of Phase One, we expect to understand:

- The extent of validation capabilities for a simple cloud-native service provider
- Functional elements of a high quality machine-readable validation and assessment package
- How PaaS/IaaS cloud services might support customer validation and assessment
- How third party compliance tools might support customer validation and assessment
- How materials created for a SOC 2 Type 2 Audit might reduce the documentation burden
- How 3PAOs might leverage machine-readable packages with primarily automated validations for assessment

Qualifying cloud service offerings that successfully complete Phase One will receive a 12 month FedRAMP Low authorization and will be prioritized for FedRAMP Moderate authorization in Phase Two. Federal agency sponsors are welcome but are not required to participate in Phase One. 

## Who should participate? {#who}

The FedRAMP 20x Phase One pilot is open to the public. FedRAMP anticipates interest from many parties and encourages participants to self-organize based on established relationships between cloud service providers, host service providers, third party services, and independent assessment organizations.

Cloud service providers that meet the following criteria are most likely to qualify for a FedRAMP Low authorization during Phase One:

-   Deployed on an existing FedRAMP authorized cloud service offering
	-   Using primarily cloud-native services from the host provider
	-   Using only FedRAMP authorized external services
-   Service is provided only via the public internet (browser and/or APIs)
-   Has completed a SOC 2 Type 2 audit or federal agency ATO process within the last 12 months
-   Has a 3PAO ready to conduct a pilot 20x assessment informed by the Key Security Indicators

## How to Participate {#how}

The FedRAMP 20x Phase One pilot will be coordinated in public across FedRAMP’s Community Working Groups:

- [Automating Assessment]({{"/20x/working-groups/automation" | relative_url}})
- [Applying Existing Frameworks]({{"/20x/working-groups/existing-frameworks" | relative_url}})
- [Continuous Reporting]({{"/20x/working-groups/reporting" | relative_url}})

Participants may self organize and/or cooperate based on mutually desired outcomes. FedRAMP will provide support and clarification during the pilot about whether proposed solutions may or may not meet Key Security Indicators to inform participants. 

The proposed FedRAMP 20x Phase One Key Security Indicators have been published for public comment in RFC-0006. The comment period will be open for 30 days. FedRAMP expects to rapidly integrate comments to formalize final Key Security Indicators and begin accepting Phase One pilot submissions for review within a week of finishing the RFC. Pilot submissions will be reviewed in order of submission so participation during the public comment period is encouraged.

After Phase One Key Security Indicators are finalized, pilot participants can submit a machine readable package that demonstrates a continuous, automated validation approach for a significant portion of the Key Security Indicators. These packages should include at least:

- Summary of the cloud service provider and cloud service offering
- Summary of and rationale for the approach used to generate the submission
- Summary from a 3PAO explaining the approach used for assessment
- Machine-readable assessment and validation package with the status of each KSI Validation, including supporting evidence and integrated verification by a 3PAO
- Data definition or data schema that explains the machine-readable package
- Proposal or prototype for continuously reporting on a significant percentage of KSI Validations

_Note: Details of the requested package may change during the initial pilot based on feedback._

This pilot is intended to showcase innovative approaches that meet FedRAMP security requirements and can be reused by others. Pilot submissions should be showcased for the public to the greatest extent possible. If a cloud service provider wishes the assessment and validation package to remain confidential, they should showcase an alternative version using realistic non-sensitive data.

FedRAMP encourages innovative solutions that use a first principles approach. Pilot participants should not feel constrained by existing technologies or processes. 

For consideration or reference, the FedRAMP team proposes one example for how a cloud service provider might approach participation below.

## Example Participant Experience {#example}

### Step One: Key Security Indicators and Validations

A pilot participant might begin by reviewing the most updated version of the FedRAMP Key Security Indicators. Each KSI defines a security objective and lists multiple KSI Validations which, when met, demonstrate that a system has achieved the security objective. A pilot participant would provide a true/false assertion to each KSI Validation.

### Step Two: Validation Evidence

A pilot participant might provide evidence to support each KSI Validation with an assertion of “true”. For this initial pilot, there is no prescribed list of acceptable evidence, and supporting evidence can be provided in many ways. For example:

- The host infrastructure or a compliance service provides a technical attestation that an offering is configured in a way that meets a KSI Validation.
- Materials for an existing SOC 2 audit demonstrates compliance with the KSI Verification
- A 3PAO assesses the service offering and validates that the KSI Verification is implemented
- Another method proposed by the cloud service provider 

### Step Three: Automation and Machine Readable Data Requirements

A pilot participant might assemble a machine-readable package that addresses each Key Security Indicator Validation. This package would include the KSI Validation assertions from Step One, and their associated evidence from Step Two. This package would be submitted in a machine readable format of a pilot participant’s choosing and design, with the following criteria:

- The machine-readable package can be regenerated on demand.
- The package includes a data definition or data schema explaining how the submission maps to the KSI elements

### Step Four: Continuous Reporting Indication

Pilot submissions might indicate which of their KSI Validations can be reported on continuously. This involves identifying which KSI Validation Evidence is generated by an automated process that executes continuously without human intervention.

Preferably, this indication would appear in the machine-readable data format, and would include meta-data of where and when the evidence was collected.

### Step Five: 3PAO Review

All 20x packages would be reviewed by a 3PAO prior to submission.

### Step Six: Prototype for Continuous Reporting

Pilot participants might use the indications developed in step four to develop a proposal or prototype for continuously reporting on those KSI Validations. This could look like:

- Designing an API interface that serves the latest security status of the system
- Deploying a static URL endpoint that can serve the latest security status of a system

### Step Seven: Red Team Exercise

After submission of the pilot package, the FedRAMP PMO may request that a pilot participant complete a red team exercise. In this case, a CSP will be notified in advance with more details.



