---
layout: default
title: Privacy Policy – Personal Tools
---

# Privacy Policy

**Last updated: 2026-10-09**

## Overview

This policy covers the personal applications listed below. They are built and run by their owner (Andris Kostiks) on his own hardware, for himself and for members of his household whom he invites personally ("users"; currently two people). They are not commercial products, are not offered to the public, and nobody can sign up for them.

- **Personal Finance Tool** — aggregates a user's own bank accounts and transactions.
- **Journal** — a user's private journal, enriched with their own health, fitness, email and calendar data.

Each user has a separate journal with its own storage, its own Google connection and its own list of devices allowed to reach it. A user's journal shows only that user's data; no user can see another user's data through the applications.

## Data collected

All access is **read-only**. No application can make payments, send or delete email, create or change calendar events, or change data at its source in any other way.

**Personal Finance Tool** (via the Enable Banking PSD2 AISP interface):

- Account identifiers and balances
- Transaction history (amounts, dates, counterparty names, descriptions)
- Session tokens required to maintain bank connectivity

**Journal**:

- Entries, photos and voice notes the user writes or records
- From the **Google Health API** (read-only scopes for activity and fitness, sleep, and health metrics and measurements): steps, workouts, sleep sessions, heart rate, weight and similar measurements
- From **Gmail** (read-only scope `gmail.readonly`): the user's email messages, so the journal can mention what is waiting for them and remember dates mentioned in mail
- From **Google Calendar** (read-only scope `calendar.readonly`): the user's calendar events, so the journal's calendar matches their real one
- From the user's own Yazio and Hevy accounts, if they connect them: logged meals and workouts
- OAuth tokens required to maintain these connections

## How data is used

Data is used only to show each user their own finances, health, mail, calendar and history, and to let a language model that runs **on the owner's own hardware** summarize it and answer that user's questions. Data is not used for advertising, is not sold, and is not used to train any model.

## How data is stored

All data is stored locally on the owner's personal hardware. It is never transmitted to any third party, cloud service or remote server other than the data sources listed above, which are contacted only to fetch the owner's data. The applications are reachable only from the owner's machine and from devices each user has been allowed on his private network; they are not exposed to the public internet. The one exception is a single address of the Personal Finance Tool that receives the bank's redirect after the user approves access at their bank; it accepts nothing else.

## Google user data

The Journal's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Google user data is used only to provide the features described above to the user it belongs to, is never transferred to others, is never used for advertising, and is never read by any human other than that user.

## Data retention and deletion

Data is retained for personal record-keeping. Any user may ask the owner to delete their data at any time, and it is then deleted from the owner's hardware. Google access can be revoked at any time at [myaccount.google.com/permissions](https://myaccount.google.com/permissions); the stored tokens are then useless and are deleted with the application's data.

## Third-party access

No third parties have access to any data collected by these applications. The owner administers the hardware the data is stored on; he does not read other users' data and accesses it only when that user asks, for example to fix a problem or delete it.

## Contact

Andris Kostiks — kostiksandriss@gmail.com
