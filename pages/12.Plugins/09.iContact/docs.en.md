---
title: iContact
media_order: ''
body_classes: ''
order_by: ''
order_manual: ''
taxonomy:
    category:
        - docs
---

-------------------

## iContact integration

[Mautic][mautic] can push contacts to [iContact][iContact] based on [Contact actions][testing] or [Point Triggers][points].

> **Note**
>
> In this document, there may be references to outdated terminology such as
>
> - _leads_,
> - _lists_ or _lead lists_, and
> - _anonymous leads_
>
> In [Mautic version `1.4`][release-1.4.0],
>
> - _leads_ were renamed to _**contacts**_
> - _lead lists_ were renamed to _**segments**_
> - _anonymous leads_ were renamed to _**visitors**_


## Authorize

In order to connect your [iContact][iContact] account with [Mautic][mautic], you'll have to create an [iContact APP][iContact-app].

Follow the [tutorial][iContact-app] to create your [iContact APP][iContact-app].

When you have your [APP][iContact-app] created, you should be able to see this screen:

![iContact - create a App Key](plugins-icontact-authorization-details.png "iContact - create a App Key")

## Configure the plugin

1. Follow [these-steps][field-mapping] to configure the plugin.


## Test the plugin

Follow [these steps][testing] to test the integration.

[iContact]: <https://www.icontact.com>
[iContact-app]: <https://www.icontact.com/developerportal/documentation/register-your-app/>\
[release-1.4.0]: <https://github.com/mautic/mautic/releases/tag/1.4.0>
[mautic]: <https://mautic.org>
[field-mapping]: </plugins/plugin-resources/field-mapping>
[testing]: </plugins/plugin-resources/testing-integrations>
[points]: </points>
