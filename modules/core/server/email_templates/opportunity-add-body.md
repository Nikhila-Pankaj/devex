{{#markdown this}}

### Hi {{data.username}}!

We've just posted a new opportunity:

**{{ data.name }}**

- Value: **{{ data.earn }}**
- Closes on: **{{ data.deadline_format_date }}**

### [See the details]({{ data.domain }}/opportunities/{{ data.opptype }}/{{ data.code }})


Have a great day!
**The BCDevExchange Team**
![BCDevExchange](https://bcdevexchange.org/modules/core/client/img/logo/logo-150px.png)

---

If you don't want these alerts, [unsubscribe now]({{ data.domain }}/api/unsubscribe/{{ data.subscriptionId }}) or manage your notification preferences in your profile at [bcdevexchange.org](http://bcdevexchange.org).

{{/markdown}}
