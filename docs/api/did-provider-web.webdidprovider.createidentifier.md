---
id: did-provider-web.webdidprovider.createidentifier
title: WebDIDProvider.createIdentifier() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## WebDIDProvider.createIdentifier() method

<b>Signature:</b>

```typescript
createIdentifier({ kms, alias, options }: {
        kms?: string;
        alias?: string;
        options: any;
    }, context: IContext): Promise<Omit<IIdentifier, 'provider'>>;
```

## Parameters

| Parameter               | Type                                            | Description |
| ----------------------- | ----------------------------------------------- | ----------- |
| { kms, alias, options } | { kms?: string; alias?: string; options: any; } |             |
| context                 | IContext                                        |             |

<b>Returns:</b>

Promise&lt;Omit&lt;[IIdentifier](./core.iidentifier.md) , 'provider'&gt;&gt;
