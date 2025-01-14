---
id: managing-testers
title: Managing Testers
sidebar_label: Managing Testers
---

import useBaseUrl from '@docusaurus/useBaseUrl';
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

To see all the testers you have for your app, invite new testers, or import/export a list of testers, click on the **TESTERS** tab.

<img src={useBaseUrl('/img/test-fairy/testing-an-app/invite-testers.png')} alt="alt upload"/>

## Inviting Testers by Email

To invite testers by email, click on the **Add Testers**.
In the list box, add tester emails - one for each row.

You can also select a Group for the testers in the list or leave it blank (see **Managing tester groups** below).
After you finish, click **Add Testers** below the list to complete the process.

You can add testers manually or [import lists of testers](https://app.testfairy.com/testers/import/) in CSV format.

:::note Only for iOS
If you are **not** using an [iOS Enterprise certificate](https://developer.apple.com/programs/ios/enterprise/), you must get the UDIDs of your testers' devices before sending them your app.
When you invite new testers by email, your testers get an email asking them to register their device. Once they click on the registration link, you get an email with their UDID, and their device details will be added to your [testers page](https://app.testfairy.com/testers).
For more information about how to add UDIDs to provisioning profiles, read [this guide](/test-fairy/sdk/ios/adding-udids).
:::

<img src={useBaseUrl('/img/test-fairy/testing-an-app/invite-testers2.png')} alt="alt upload"/>

## Managing Tester Groups

You can also divide testers into **groups** to add more structure and organize your testing efforts.
To create a group, click in the GROUPS text box and then on `Create new group...`
Choose a group name and click OK. The tester you clicked in their group will be assigned the group you created.

<img src={useBaseUrl('/img/test-fairy/testing-an-app/tester-groups-1.png')} alt="alt tester group"/>

Tester groups help you manage the invitation process to your apps. If you want to invite several testers that are all under the same group, filter the list of testers according to that group and then select all and invite them.

<img src={useBaseUrl('/img/test-fairy/testing-an-app/tester-group-2.png')} alt="alt invite group"/>

To delete a group, you must first delete all its mentions in the GROUPS field. Delete the group by pressing the x next to its name. Once you have deleted all its occurrences, it will be deleted. Then, refresh the page to make sure it was deleted.

<img src={useBaseUrl('/img/test-fairy/testing-an-app/delete-group.png')} alt="alt delete group"/>
