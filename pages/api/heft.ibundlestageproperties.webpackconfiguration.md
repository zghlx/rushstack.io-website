---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft](./heft.md) &gt; [IBundleStageProperties](./heft.ibundlestageproperties.md) &gt; [webpackConfiguration](./heft.ibundlestageproperties.webpackconfiguration.md)

## IBundleStageProperties.webpackConfiguration property

The configuration used by the Webpack plugin. This must be populated for Webpack to run. If webpackConfigFilePath is specified, this will be populated automatically with the exports of the config file referenced in that property.

<b>Signature:</b>

```typescript
webpackConfiguration?: webpack.Configuration;
```
