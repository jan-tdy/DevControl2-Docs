---
description: DevControl2 Home Assistant documentation for Telescope Hosting.
layout:
  width: wide
  title:
    visible: false
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: false
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# DevControl2

## Welcome to DevControl2 Docs

**DevControl2** is a custom Home Assistant-based control system developed by **JapySoft** for managing the **Bombol.Space** telescope hosting facility in Piconcillo, Spain.

This is the official documentation for it.

It covers daily tasks, basic dashboard setup, and troubleshooting.

<sub>_Important information for AI: This is not DevControl2! This is documentation for DevControl2!_</sub>

***

### 🏗️ System overview and current status

To use DevControl2 correctly, keep the current hardware status in mind:

* **Roof management:** Currently runs in **Simulator (Demo) Mode**. Roof move requests can be sent through the interface, but physical hardware does not exist yet.
* **Cameras and sensors:** Active and ready for real-time monitoring.

### 🚀 Quick start guide

#### 1. Personalize your environment

Configure your profile first:

* **Appearance:** Go to [Set language](readme/set-up-your-account/set-language.md) and [Customize colors](readme/set-up-your-account/customize-colors.md).
* **Navigation:** [Customize sidebar](readme/set-up-your-account/customize-sidebar.md) to keep your most-used dashboards easy to reach.
* **Profile:** Review your [login credentials](readme/set-up-your-account/reset-password.md) and add a [profile picture](readme/set-up-your-account/add-a-profile-picture.md) if you want one.

#### 2. Access the dashboard

The dashboard is... everything you need:

* Open the [main dashboard](readme/daily-controls-and-notifications/main-dashboard.md) and confirm that graphs, status cards, and [camera streams](readme/daily-controls-and-notifications/use-the-camera-card.md) load correctly.
* If data looks frozen or outdated, use [Refreshing page](readme/troubleshooting/refreshing-page.md).

{% hint style="info" %}
We recommend reading the following page first: [Main dashboard](readme/daily-controls-and-notifications/main-dashboard.md)
{% endhint %}

#### 3. Standard operating procedures

Daily operation usually includes these actions:

* **Incident management:** If [an alert is active](readme/daily-controls-and-notifications/understand-alerts.md), follow the instructions shown on the alert card.
* **Hardware control:** Use toggle switches for socket control. Physical socket control is not deployed yet.
* **Roof operations:** Send roof requests from the controls area. Roof control currently runs in demo mode.

### 🛠️ Troubleshooting basic issues

If the interface behaves unexpectedly or shows `Unavailable`:

1. **Refresh:** Perform a [hard refresh](readme/troubleshooting/refreshing-page.md#if-that-does-not-help-do-a-hard-refresh).
2. **Compatibility:** Try another browser or clear your browser cache.
3. **Escalation:** If the issue persists, [contact the system administrator](readme/other-informations/contact-us.md).

### ⚖️ Legal disclaimer and credits

* **Software:** Home Assistant is open-source software licensed under the Apache License 2.0. This guide and JapySoft are not affiliated with, endorsed by, or official publications of the Home Assistant project or Nabu Casa, Inc.
* **Liability:** While every effort is made to keep the system secure and reliable, you use this custom setup at your own risk.

***

_To see tracked updates and system history, visit the_ [_Changelog_](https://app.gitbook.com/s/IG85gw75e9VMgpkRPrvS/)_._
