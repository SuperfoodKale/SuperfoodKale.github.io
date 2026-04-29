---
layout: single
title: "DSL Connectivity Fault Diagnosis and Cable Replacement"
---

## Context

A home network environment with persistent internet connectivity issues characterised by frequent dropouts. The fault presented intermittently rather than as a total outage, requiring systematic isolation to distinguish between ISP infrastructure, physical cabling, and internal network equipment.

## Symptoms

- Frequent internet dropouts across all household devices
- Connectivity unreliable rather than fully absent
- No consistent trigger or pattern identified for dropout events

## Initial Assessment

- Intermittent dropout behaviour suggested the fault could lie anywhere from ISP infrastructure through to the modem or internal network equipment
- Systematic elimination from the external connection inward considered the most efficient diagnostic approach
- Potential causes included ISP-side outages or degradation, faulty or aging physical cabling, and modem hardware failure

## Investigation

- Observed the DSL connection indicator on the modem was not stable, pointing to a fault upstream of the internal network
- Contacted ISP support, who confirmed no faults or outages on their end, isolating the fault to the physical connection between the premises and ISP infrastructure
- The premises had two DSL wall ports in separate locations; moved the existing cable from the first wall port to the second to test whether the fault was specific to that connection point
- Dropouts persisted on the second port, suggesting either the house wiring or the DSL cable itself was at fault
- Replaced the active DSL cable with a new cable; connectivity was immediately restored and dropouts ceased
- Identified the original cable as aging, consistent with the observed intermittent failure behaviour and gradual signal degradation rather than a complete break

## Root Cause

Aging cabling had deteriorated to a point where signal integrity was compromised but not fully lost, explaining the intermittent dropout pattern rather than a complete outage.

## Resolution

- Replaced the faulty DSL cable with a new cable, restoring stable internet connectivity
- Further upgraded the home network by running a direct Cat6 Ethernet connection from the modem to the primary household PC, improving reliability and throughput for the main device over the previous Wi-Fi path

## Outcome

Internet connectivity was fully restored and remained stable following the cable replacement. The additional Ethernet upgrade provided the primary PC with a more reliable and higher-performance connection, removing Wi-Fi as a variable for that device entirely.

## Key Takeaway

Intermittent connectivity faults are among the more tedious to diagnose because they resist consistent reproduction. Systematic, component-by-component elimination from the external connection inward, changing one variable at a time, combined with ISP confirmation to establish the fault boundary, significantly narrows the search space and avoids time spent chasing internal network issues that are not responsible for the failure.
