---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor](./api-extractor.md) &gt; [ExtractorConfig](./api-extractor.extractorconfig.md) &gt; [apiJsonFilePath](./api-extractor.extractorconfig.apijsonfilepath.md)

## ExtractorConfig.apiJsonFilePath property

The output path for the doc model file. The file extension should be ".api.json".

<b>Signature:</b>

```typescript
readonly apiJsonFilePath: string;
```

## Remarks

The path is resolved relative to the folder of the config file that contains the setting; to change this, prepend a folder token such as `<projectFolder>` .