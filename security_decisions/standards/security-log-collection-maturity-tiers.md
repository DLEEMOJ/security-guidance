---
category: Security Log Collection
expires: 2020-12-31
---

# Security Log Collection Maturity Tiers

MOJ systems and services must adequately create and retain event data as part of the [DETECT](https://ministryofjustice.github.io/security-guidance/principles/identify-protect-detect-respond-recover/#detect) portion of the [Cabinet Office's Minimum Cyber Security Standard (MCSS)](https://www.gov.uk/government/publications/the-minimum-cyber-security-standard).

Three tiers have been developed to reflect the breadth and complexity of collecting and forwarding log data.

These three tiers represent different levels of risk profile, and concern about a system.
All systems should be capable of meeting the baseline standard.

Some systems are at greater likelihood of compromise.
This is due to factors such as age or public threats.
Other systems would have a higher impact if compromised.
This is due to the systems being sensitive or having distinctive perceived value.
Such systems should be monitored to a higher standard.

The extent to which a security log collection process implements the monitoring requirement indicates the logging maturity.

Each level of monitoring - or 'tier' - has characteristics that are 'in addition' to lower level tiers.
For example,
a system operating at the Enhanced tier should also meet the requirements of the Baseline tier.

![](https://ministryofjustice.github.io/security-guidance/images/Tiers.png)

## Baseline

The baseline tier is the generally minimum expected for event types.
It includes data that should be generated, recorded, and forwarded for onward analysis.
It applies to all of the MoJ systems.
In most cases, this requirement may be met through the underlying platform(s) on which the systems are built.

This tier covers the broad spectrum of events that can reasonably be used to detect compromise.
It allows the defensive cyber team to respond appropriately before significant impact.

## Enhanced

The enhanced tier, in conjunction with the baseline event types, provides earlier notification of attempted compromise.
It enables gathering of more information to detect stealthier or more capable attackers.

## Bespoke

The bespoke tier concerns systems that are critical to the security, stability and statutory function of the MoJ, or that contain highly sensitive data.
In this tier, systems must generate additional bespoke (customised) event types.
These event types are typically agreed in context between the MOJ Cyber Security team and the associated product or service team.
The objective is produce logging that reliably identifies and captures key nuance and contextual security monitoring data, based on applicable threats and risks.

---

Last updated: April 20th, 2020.
