---
title: Voluntarily provide stakeholder feedback
description: Voluntarily provide stakeholder feedback in Azure DevOps using the Exploratory Testing browser extension when you want to test your applications.
ms.assetid: 4E467527-62C6-4321-BA56-FF82F0FFFD69
ms.service: azure-devops-test-plans
ms.custom: UpdateFrequency3
ms.topic: conceptual
ms.author: rbatra
author: rohit-batra
ms.date: 12/07/2018
monikerRange: '<= azure-devops'
---

# Voluntarily provide stakeholder feedback using the Test &amp; Feedback extension

[!INCLUDE [version-lt-eq-azure-devops](../includes/version-lt-eq-azure-devops.md)] 

[!INCLUDE [feedback-header-text](includes/feedback-header-text.md)] 

<a name="voluntary"></a>
## Provide voluntary feedback  

You can use the Test &amp; Feedback extension to provide feedback
voluntarily, even if you haven't received a specific
[feedback request](request-stakeholder-feedback.md#request). 

1. Open the Test &amp; Feedback extension in your browser using the
   ![launch exploratory testing](media/shared/exp-test-icon.png)
   icon in the toolbar. 

1. In the **Connection settings** page, choose **Connected** mode.
 
   ![Choosing Connected mode](media/shared/connectedmode-01.png)
 
1. Connect to the server and the project or team that is requesting feedback.
 
   ![Entering connection details](media/shared/connectedmode-02.png)

1. Start the exploratory testing session.

   ![Starting the exploratory testing session](media/voluntary-stakeholder-feedback/voluntary-stakeholder-feedback-26.png)

1. Open the application you want to provide feedback on
   and begin your feedback. For example, choose 
   **Capture screenshot** to take a screenshot.
 
   ![Capturing a screenshot](media/voluntary-stakeholder-feedback/voluntary-stakeholder-feedback-27.png)

   You can use all the capabilities of the extension
   such as capturing screenshots, notes, and screen recordings.

   >Some browsers may not provide all of the capture capabilities.
   See [Supported web browsers for the extension](perform-exploratory-tests.md#browser-support).
 
1. When you are done capturing feedback, Choose **Provide feedback**.

   ![Submitting your feedback](media/shared/provide-stakeholder-feedback-08.png)

   You can optionally choose to create bugs and tasks when you 
   submit your feedback. The process is the same as described 
   [here](connected-mode-exploratory-testing.md#create-bugs).
 
1. All your feedback captured is shown in the response form. 
   Type a suitable title and, optionally, select a star rating for 
   the feature you've been testing. 

   ![Entering a title and star rating](media/shared/provide-stakeholder-feedback-09.png)

1. Save your feedback. This create a work item in Azure DevOps containing all your feedback.
 
1. Continue to capture more feedback if required. You can submit 
   multiple feedback responses, bugs, and tasks for the same feedback request. 

1. Choose the **Stop** icon to end your feedback session. 
     
   ![Ending your feedback session](media/shared/provide-stakeholder-feedback-12.png)

## Related articles

* [Request stakeholder feedback using the Test &amp; Feedback extension](request-stakeholder-feedback.md#request)
* [Provide stakeholder feedback using the Test &amp; Feedback extension](provide-stakeholder-feedback.md#provide)
* [Track stakeholder feedback using the Test &amp; Feedback extension](track-stakeholder-feedback.md#track)
* [Exploratory test and submit feedback directly from your browser](perform-exploratory-tests.md)
* [Overview of manual and exploratory testing](index.yml)

 
