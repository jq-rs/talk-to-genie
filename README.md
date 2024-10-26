# Navigators Season 2: Growth Grants Proposal

## Title
Talk to Genie

## Project Background

Software licensing is a hard problem. Privacy, anonymity, and ease of use are difficult to offer.

## Proposal Overview

An AI called "Genie" can be called out and discussed over a chat after reclaiming a license via zkApp.

- **Problem:** How to license software or features in a privacy-respecting way easy for the user.
- **Solution:** Use zkApp combined with zkOracle for software licenses.
- **Impact:** Example use case where zkApp can provide novel ways to improve existing technologies.
- **Audience:** All software developers and firms that license their software and want to do it in a privacy-respecting way.


## Architecture & Design

- **Detailed Design/Architecture:** Design and implement zkApp that is used for software licensing. Design and implement a zkOracle to save extra information for the license. Create APIs for license handling. Ensure that privacy and anonymity are preserved. Save only licensing Merkle root on-chain and rest into zkOracle off-chain. Verify both off-chain and on-chain when checking license validity. Allow to set expiry time for the license in questing. Ensure that several license instances can use the same zkApp.
- **Vision:** Revolutionize software licensing with zkApps. 
- **Project Timeline :** 3M
- **Existing Work:** Rust REST API server exists and can be extended for zkOracle use case.
- **Production Timeline :** In 3 months


##  Budget & milestones

- **Deliverables**: 1st month for zkApp creation and testing, 2nd month for zkOracle and 3rd month for finalization.
- **Mid-Point milestones:** Working PoC for zkApp and zkOracle. 
- **Budget Requested :** 10,000 MINA
- **Budget Breakdown:** Development and environment costs.
- **Wallet Address:** B62qooDptPZvwHcK7QmJ5Db1c48sJAR8hFVER2vwRGWx7k2SShQZEaT

## Team Info

-  **Proposer Github**: github.com/jq-rs
- **Proposer Experience**: Basic information, zkIgnite Cohort 0 grantee of 50 MINA.
-  **Team Members**: I am the only member
-  **Achievements**: Long-time MINA supporter.


## Risks & Mitigations

Unexpected O1js issues regarding building the zkApp. Mitigations are contacting Discord zkApp experts for support.

