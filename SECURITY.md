# Security Policy

## Reporting a Vulnerability

Report security issues by emailing the maintainers at security@metalctrl.io - do NOT log public issues for security vulnerabilities.

To ensure the timely response to your report, please ensure that the entirety of the report is contained within the email body and not solely behind a web link or an attachment.

The maintainer(s) and Security Team will acknowledge your email as quickly as possible, and will send a more detailed response indicating the next steps in handling your report. After the initial reply to your report, the security team will endeavor to keep you informed of the progress towards a fix and full announcement, and may ask for additional information or guidance.

We will _strive_ to respond to submissions within 48 hours but given this project is fully open source and ramping up adoption, feature sets, do not expect consistent replies within any specific time frame.


## Public Disclosure Process

The Security Team publishes a public advisory to the Infratographer community via GitHub. In most cases, additional communication via Slack, blog and other channels will assist in educating Infratographer users and rolling out the patched release to affected users.

The Security Team will also publish any mitigating steps users can take until the fix can be applied to their Infratographer instances. Infratographer distributors will handle creating and publishing their own security advisories.

## Confidentiality, Integrity and Availability

We consider vulnerabilities leading to the compromise of data confidentiality, elevation of privilege, or integrity to be our highest priority concerns. Availability, in particular in areas relating to DoS and resource exhaustion, is also a serious security concern. The Infratographer Security Team takes all vulnerabilities, potential vulnerabilities, and suspected vulnerabilities seriously and will investigate them in an urgent and expeditious manner.

Note that we do not currently consider the default settings for Infratographer to be secure-by-default. It is necessary for operators to explicitly configure settings, role based access control, and other resource related features in Infratographer to provide a hardened Infratographer environment. We will not act on any security disclosure that relates to a lack of safe defaults. Over time, we will work towards improved safe-by-default configuration, taking into account backwards compatibility.
