# Defining Constants

{% hint style="info" %}
**Constants:** A globally defined variable that can be utilized in .yaml configuration files for Live Interactions, Live Commands, and Triggers.
{% endhint %}

## Customization

A **Tasukete** admin can set constants for anything:

* Discord ID's:
  * Channel ID
  * Role ID
* Colors

```yaml
ROLES:
  SUPPORTER: "Discord_role_ID"
  
CHANNELS:
  WELCOME: "Discord_channel_ID"
  
COLORS:
  WHITE: 0xFFFFFF
```

To utilize constants in configuration files of **Tasukete:**

```yaml
${ ROLES.SUPPORTER }
${ CHANNELS.WELCOME }
${ COLORS.WHITE }
```
