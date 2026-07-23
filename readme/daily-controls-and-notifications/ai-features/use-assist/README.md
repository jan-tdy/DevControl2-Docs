---
description: Ask Home Assistant Assist about configured DevControl2 data.
icon: message
---

# Use Assist

{% stepper %}
{% step %}
### Open Assist

Select the message bubble at the upper-right corner of the main dashboard.

<figure><img src="../../../../.gitbook/assets/Screenshot_20260419_141736.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Ask a question

Ask one clear question at a time.

{% hint style="info" %}
_Requesting a roof move is planned but not supported yet._
{% endhint %}

{% hint style="danger" %}
To avoid API error codes, please don't spam the assistant. About 5 questions per minute is the safe limit.
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Screenshot_20260419_142149.png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

### What Assist can answer

Assist can answer questions about available, configured Home Assistant data. This includes solar input, EcoFlow battery status, Tapo door positions, and observing conditions.

### What Assist cannot safely do

Assist does not replace safety checks or facility procedures. Do not use it as the only source for roof, weather, power, or emergency decisions.

Roof-move requests are not supported. Confirm dashboard states before acting.

### Example questions

* “What is the EcoFlow battery level and input power?”
* “Is the control room door open?”
* “What are tonight’s observing conditions?”
