<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Network](./puppeteer.protocol.network.md) &gt; [ResponseReceivedExtraInfoEvent](./puppeteer.protocol.network.responsereceivedextrainfoevent.md) &gt; [blockedCookies](./puppeteer.protocol.network.responsereceivedextrainfoevent.blockedcookies.md)

## Protocol.Network.ResponseReceivedExtraInfoEvent.blockedCookies property

A list of cookies which were not stored from the response along with the corresponding reasons for blocking. The cookies here may not be valid due to syntax errors, which are represented by the invalid cookie line string instead of a proper cookie.

<b>Signature:</b>

```typescript
blockedCookies: BlockedSetCookieWithReason[];
```
