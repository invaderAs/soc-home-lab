## Lab Architecture

This diagram shows the basic architecture of the SOC home lab.

- **Parrot OS** is used to simulate attack or suspicious activity.
- **Windows 10** acts as the monitored endpoint and generates security events.
- **Ubuntu SIEM (Wazuh)** receives logs from the Windows endpoint for analysis and alerting.

Arrows in the diagram represent the logical flow of activity and logs:
- Simulated activity flows toward the Windows endpoint.
- Security logs flow from Windows to the SIEM.

The diagram is intentionally simple to focus on visibility and log flow
rather than detailed network connectivity.
