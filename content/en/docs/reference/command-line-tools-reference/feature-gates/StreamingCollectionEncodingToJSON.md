---
title: StreamingCollectionEncodingToJSON
content_type: feature_gate
_build:
  list: never
  render: false

stages:
  - stage: alpha 
    defaultValue: true
    fromVersion: "1.33"

---
Allow the API server JSON encoder to encode collections item by item, instead of all at once.
