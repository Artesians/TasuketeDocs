# Creating a Trigger

{% hint style="info" %}
**Trigger:** A pre-defined keyword or specific pattern (Regular Expression) that creates an auto-response from **Tasukete**.
{% endhint %}

## Tasukete Triggers

**Tasukete** uses .yaml files to define keywords and patterns as well as the auto-response.

## Customization

**Tasukete** is able to generate embeds that can be interacted with by the user. Buttons and drop-down menus are able to be used to navigate to other Live Interactions. A **Tasukete** admin can set the parameters that define the following:

* Match (keyword or pattern)

{% embed url="https://artesians.gitbook.io/tasukete-documentation/guides/creating-a-live-command#customization" %}
Triggers can also be customized in the same manner Live Commands are able to.
{% endembed %}

```yaml
match: "(nati|rati|natxia|eternati)onal"
interaction: triggers/national
```

![](<../.gitbook/assets/Trigger (1).png>)
