---
id: gdpr
title: GDPR
sidebar_label: GDPR
---

import useBaseUrl from '@docusaurus/useBaseUrl';
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

The EU General Data Protection Regulation (GDPR) was designed to harmonize data privacy laws across Europe, protect and empower all EU citizens' data privacy, and reshape how organizations across the region approach data privacy.

Following these regulations, here are some answers to your questions:

## Can TestFairy Provide a GDPR-Compliant Service?

Yes. TestFairy can provide a GDPR-compliant service to customers on a Private Cloud or On-Premise installations. Contact us for more details.

## Can TestFairy Provide Full Transparency?

Yes. TestFairy end-users are ensured that their data is only used by TestFairy for legitimate purposes, meaning for the purpose intended by the developers who use our platform. We do not and will never sell, transfer or otherwise harm your data, and we make sure it is only used via our services.

## Can TestFairy End-Users See Their Sessions?

Yes. On a Private cloud or on an on-prem installation, companies can allow their end-users to see their recorded sessions. The developer must identify the sessions using the SDK function [setUserId](/test-fairy/sdk/identifying-users).
Users can only see their sessions by logging into TestFairy via their desktop browser. At the moment, mobile view is not supported.

## Can TestFairy Users Request to Delete Their Sessions?

Yes. On a Private cloud or on an on-prem installation, it is possible for companies to allow their end end-users to request to delete their sessions. A deletion request is done by clicking on the delete button at the top right corner of every session.
The deletion request will be sent to the account owner, who will confirm the deletion.
It is essential to mention that the account owner deletes data under their responsibility.

<img src={useBaseUrl('/img/test-fairy/security/delete-btn.png')} alt="Create bug"/>

## Can TestFairy End-Users See a Notification Explaining What Is Going To Be Recorded?

TestFairy requires customers to notify users that they are recorded. It can be done in the app TOS that must be straightforwardly accessible and effortless to read and understand, and also possible to display a visual dialog (pop-up) when the app starts, explaining to the user that they are recorded for quality assurance purposes and how they can request to delete their data.
In case of showing a visual disclaimer, this should be done before calling the function TestFairy.begin.

## Can TestFairy Data Be Automatically Deleted After 30 Days?

Yes. TestFairy can automatically delete sessions over 30 days or any period your company requires. Deletion is permanent and can not be undone.

## Can the Service Be Hosted in Europe?

Yes. In addition to the US, Private Clouds can also be hosted on AWS in the UK, Germany, and France.
