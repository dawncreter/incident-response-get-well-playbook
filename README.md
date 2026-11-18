# Incident Response & Get-Well Playbook (Syniverse)

> How incident command, root-cause problem management and get-well plans raised availability for 92 live telecom products from 99.9369% to 99.999% — and how we cut over an $867M acquisition with zero customer downtime.

*Based on my work as Head of Change Management, Release Management and Incident Response at Syniverse. No proprietary data.*

## Scope
- **92 live commercial products**: mobile voice, SMS, SS7 and IPX services for carriers worldwide
- **20+ person matrix team** across the US, India and Costa Rica, including **8 Incident Response Managers**
- Change, release and incident governance through **ServiceNow ITSM** and a **Change Control Board**
- Data center migrations across Dallas, Chicago, Tampa, Amsterdam, Frankfurt and Tokyo

## The playbook
| Phase | What happens |
|---|---|
| **1. Command** | One incident commander, clear roles, one communication channel; outage communications automated so engineers can focus |
| **2. Restore** | Restore service first; rehearsed rollback (restore in under five minutes for cutovers) |
| **3. Root cause** | Problem management finds the underlying cause, not just the symptom |
| **4. Get well** | A get-well plan with owners and dates for every recurring issue |
| **5. Learn** | Blameless post-incident reviews; fixes feed change control so they stick |

See [`templates/`](templates/) for the post-incident review and get-well plan formats.

## Results
| Metric | Result |
|---|---|
| Availability (92 products) | **99.9369% → 99.999%** |
| MTTR | Improved |
| SLA credits | Reduced |
| Manual outage communications | Automated, freeing hours every week |
| $867M acquisition cutover | **Zero customer SLA downtime** |

## Lessons
1. **Automate the communication, not just the fix.** Freeing responders from status updates shortened every incident.
2. **A get-well plan without owners is a wish list.**
3. **Rehearse rollbacks.** Practiced rollback is what made zero-downtime cutovers possible.
4. **Report risk upward.** I presented technology risk reviews to the CIO and Board (Carlyle Group) so investment followed the data.
