<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Audits](./puppeteer.protocol.audits.md) &gt; [MixedContentIssueDetails](./puppeteer.protocol.audits.mixedcontentissuedetails.md)

## Protocol.Audits.MixedContentIssueDetails interface

<b>Signature:</b>

```typescript
export interface MixedContentIssueDetails 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [frame](./puppeteer.protocol.audits.mixedcontentissuedetails.frame.md) | [AffectedFrame](./puppeteer.protocol.audits.affectedframe.md) | Optional because not every mixed content issue is necessarily linked to a frame. |
|  [insecureURL](./puppeteer.protocol.audits.mixedcontentissuedetails.insecureurl.md) | string | The unsafe http url causing the mixed content issue. |
|  [mainResourceURL](./puppeteer.protocol.audits.mixedcontentissuedetails.mainresourceurl.md) | string | The url responsible for the call to an unsafe url. |
|  [request](./puppeteer.protocol.audits.mixedcontentissuedetails.request.md) | [AffectedRequest](./puppeteer.protocol.audits.affectedrequest.md) | The mixed content request. Does not always exist (e.g. for unsafe form submission urls). |
|  [resolutionStatus](./puppeteer.protocol.audits.mixedcontentissuedetails.resolutionstatus.md) | [MixedContentResolutionStatus](./puppeteer.protocol.audits.mixedcontentresolutionstatus.md) | The way the mixed content issue is being resolved. |
|  [resourceType](./puppeteer.protocol.audits.mixedcontentissuedetails.resourcetype.md) | [MixedContentResourceType](./puppeteer.protocol.audits.mixedcontentresourcetype.md) | The type of resource causing the mixed content issue (css, js, iframe, form,...). Marked as optional because it is mapped to from blink::mojom::RequestContextType, which will be replaced by network::mojom::RequestDestination |

