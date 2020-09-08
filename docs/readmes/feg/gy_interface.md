# Gy Interface

Objectives:
- Clearly communicate what is supported and what is not.
- Allow partner to understand how some unsuported feature can be executed with a different configuration.

## Functional Description

**TODO:** add here some context building blocks and explanation

### Protocol Stack Compliance

| Network | Transport | Application 
| --- | --- | --- | 
| IPv4 | TCP | Diameter 
| IPv4 | SCTP | Diameter 
| IPv6 | TCP | Diameter 
| IPv6 | SCTP | Diameter 

**TODO:** Add here where to configure those


## Procedures

List of supported procedures as described by [32.299] Rel 16

- Offline Charging
    - Imediate Event Charging: 
      - Not Supported
    - Event Charging with Unit Reservation
      - Not Supported
    - Session Charging with Unit Reservation
      - Not Supported
- Online Charging
    - Imediate Event Charging: 
      - Not Supported
    - Event Charging with Unit Reservation
      - Not Supported
    - Session Charging with Unit Reservation
      - Supported


## Gy Message Compliance

| Message | Abbreviation | Direction | Compliance | Supported |
| --- | --- | --- | --- | --- |
| Credit Control Request - Initiate | CCR-I | FeG -> OCS | TS 32.299 Rel ?? | Yes
| Credit Control Answer - Initiate | CCA-I | OCS -> FeG | TS 32.299 Rel ?? | Yes
| Credit Control Request - Update | CCR-U | FeG -> OCS | TS 32.299 Rel ?? | Yes
| Credit Control Answer - Update | CCA-U | OCS -> FeG | TS 32.299 Rel ?? | Yes
| Credit Control Request - Terminate | CCR-T | FeG -> OCS | TS 32.299 Rel ?? | Yes
| Credit Control Answer - Terminate | CCA-T | OCS -> FeG | TS 32.299 Rel ?? | Yes


### Credit Control Request - Initiate

#### Supported AVPs

| AVP | Supported | Notes |
| --- | --- | --- |
| Final-Unit-Action | No | 

### Credit Control Answer - Initiate

When is this trigered?

Which AVPs are cunrrently supported?

## Abbreviations

| | |
| --- | --- |
| OCS | Online Charging System
| FeG | Federeated Gateway
| PCEF | Policy Charging Enforcement Function |

## References

[TS 32.299] - Diameter charging applications: 
