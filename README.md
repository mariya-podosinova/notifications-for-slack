# Automated Event Notifications in Slack from Outlook Calendar

## Overview

This project seeks to bridge the gap between Microsoft Outlook Calendar and Slack, allowing users to effortlessly sync and share calendar events with their Slack teams. Our specific focus is on integrating 'Manchester Events' from Outlook Calendar and sending automated updates to Slack channels every week.

Previously, our implementation involved integrating Google Calendar with Slack. However, to meet the evolving needs of our team, we now aim to create a new integration with Outlook Calendar. By leveraging the power of automation, we intend to eliminate the need for manual event sharing and ensure that important 'Manchester Events' updates are seamlessly communicated within Slack channels. Our goal is to create a more connected and efficient work environment.

## Project Status

### Recent Developments

This week, our focus was on the operational aspect of our project.

- **Communication with Support**: We initiated discussions with the support team to gain the necessary permissions for platform access. However, we have encountered access limitations beyond our current authority. To learn more about our communication with support, please refer to the [PowerIntake.md](URL_TO_POWER_INTAKE_DOC) document.

- **Exploring a Bot-Based Solution**: In parallel with addressing access issues, we have been actively investigating the feasibility of implementing a bot-based solution for Slack integration.

## Table of Contents

- [Requirements](#requirements)
- [Current Progress](#current-progress)
- [Available Solutions](#available-solutions)
- [Challenges and Next Steps](#challenges-and-next-steps)
- [Contact Information](#contact-information)

## Requirements

1. **Automated Notifications from Outlook Calendar to Specified Slack Channels**:

   - The system should automate the process of sending notifications from Outlook Calendar to specified Slack channels.
   - Users should have the ability to customize the content and format of notifications, including setting notification frequency and other preferences, such as setting notifications to every Friday for all events for the following week.
   - Notifications should be sent automatically when new events are added to the Outlook Calendar or when changes are made to calendar events by the owner, ensuring timely updates in the Slack channel.

2. **User Documentation and UAT**:
   - Provide user documentation or guides explaining how to set up and use the integration.
   - Conduct User Acceptance Testing (UAT) to validate that notifications are accurate, timely, and meet user expectations.

## Current Progress

### Exploratory Phase

During the previous weeks, our primary focus was on the exploratory phase of our project. Key activities during this phase included:

- **Research and Evaluation**: We conducted comprehensive research and evaluation of potential integration approaches, aiming to identify the most suitable method for seamless integration.

- **Solution Discovery**: The exploratory phase involved discovering and assessing multiple integration options to determine the optimal path forward. We evaluated feasibility, benefits, and challenges associated with each solution.

## Available Solutions

### Overview

We've explored several potential solutions for integrating Outlook Calendar with Slack, with a primary focus on leveraging Power Automate due to its compatibility and advantages. Below, we outline the available options, along with their associated considerations.

### Solution 1: Third-Party Tools Providers (Low Priority)

👍 No need to develop a custom solution.
👎 Not free, which can add to project costs.

### Solution 2: Application Development with Microsoft Developer (Medium Priority)

👍 Total control over implementation, allowing for custom features.
👎 Requires development effort and resources; no access right now.

### Solution 3: Reusing Templates with Power Automate (High Priority)

👍 Access to a repository of ready-made templates and a large community.
👎 No access right now.

### Solution 4: Creating a Slack Bot (Low Priority)

🤷‍♂️ More research is needed to gather details and feasibility as we don't have sufficient information at the moment.

## Challenges and Next Steps

### Lack of Access to Power Automate Platform

One of the primary challenges we currently face is the **lack of access to the Power Automate platform**. We've encountered an error that prevents us from utilizing this key component of our integration plan. To address this challenge, we've taken the following steps:

- **Access Request with Power Intake**: We have requested access with Power Intake, and the request status is **InProgress**. Last week, we opened and resolved a ticket with Accenture Support, which led to the recommendation to open a request with Power Intake.

- **Microsoft Enterprise Admin Center (Microsoft Developer)**: Additionally, we are facing access issues with app registrations in the Microsoft Enterprise Admin Center (Microsoft Developer). Access is currently denied, adding complexity to our development efforts.

As we progress, we will continue to document and address these challenges while seeking solutions to overcome them.

You can view a screenshot of the error we encountered [here](https://github.com/mariya-podosinova/notifications-for-slack/blob/main/issue-screenshots/Screenshot%202023-09-11%20at%2014.29.54.png).

### Exploring a Bot-Based Solution for Slack

Additionally, we are exploring the feasibility of implementing a bot-based solution for Slack integration. This presents its own set of challenges, including the need for thorough research and development to ensure an effective and seamless integration.

## Contact Information

Have questions or need assistance? Feel free to reach out to the team:

Project Contributors:

🤝 dave.postle@accenture.com

🔍 kaily.newman@accenture.com

👨‍💻 mariya.podosinova@accenture.com

👨‍💻 yuri.aguirre@accenture.com

We're here to help and collaborate on this project!
