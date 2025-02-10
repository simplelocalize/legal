---
title: Incident Handling Process
modified: 2025-02-10
author: "Jakub Pomykała"
excerpt: "How SimpleLocalize.io detects, responds to, and communicates security incidents affecting customer data."
---

## Purpose

This document describes how SimpleLocalize.io ("we") detects, responds to, and communicates security incidents that affect the confidentiality, integrity, or availability of customer data or the service.

## Scope

An "incident" is any confirmed or reasonably suspected event that may lead to unauthorized access, disclosure, loss, or alteration of customer data, or that materially disrupts the availability of SimpleLocalize.io.

## 1. Detection

- Automated monitoring, error tracking (Sentry.io), and infrastructure alerts (AWS, Cloudflare, internal tools) flag anomalous activity around the clock.
- Reports may also come from customers, subprocessors, or team members via contact@simplelocalize.io.

## 2. Triage and classification

Upon detection, the incident is triaged and classified by severity (low / medium / high / critical) based on the scope of data or systems affected. Critical and high severity incidents trigger immediate escalation to Jakub Pomykała, who owns incident response.

## 3. Containment and eradication

- Affected systems, accounts, or credentials are isolated or revoked to stop ongoing impact.
- The root cause is identified and remediated (e.g., patching, access revocation, configuration fix).

## 4. Recovery

Services are restored from clean state or verified backups. Systems are monitored closely after recovery to confirm the issue is resolved and does not recur.

## 5. Customer notification

If an incident involves personal data processed on behalf of a customer, we notify the affected customer(s) by email **without undue delay, and no later than 48 hours** after becoming aware of it, per our [Data Processing Agreement](/dpa/). The notification includes a description of the incident, the data/systems affected, and remediation steps taken, with periodic updates until resolution.

## 6. Post-incident review

After resolution, we document a root cause analysis and any follow-up actions to reduce the risk of recurrence.

## Contact

To report a suspected security incident, email **contact@simplelocalize.io**.

## Changelog

A detailed changelog of the document can be found on our [GitHub repository](https://github.com/simplelocalize/legal).
