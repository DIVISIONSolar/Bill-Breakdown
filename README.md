# Simple bill breakdown (Will remake in either react.js or solid.js when I get the time)

# How to setup

Replace `KEY` with your API key from https://wise.com `const API_KEY = 'KEY';`

## If you want to change the currency conversions you can do so here:

```
{ name: 'Subscription #1', interval: 'Monthly', amountEUR: 24.36 },
```
Change the **EUR** to anything else for example **GBP**

also change this section:

```
const params = new URLSearchParams({
                source: 'USD',
                target: 'EUR'
            });
```
Example:

```
const params = new URLSearchParams({
                source: 'AUD',
                target: 'EUR'
            });
```
