---
layout: default
title: "Use the API"
permalink: /use_api/
---

## API Basics
The 3DPX API has four primary operations that work with _public-domain_ models*.

1. Return all models in XML format.
2. Return a specified public domain model in XML format by providing that model’s 3DPX accession code (e.g., 3dpx-######)
3. Return all public domain models in JSON format.
4. Return a specified public domain model in JSON format by providing that model’s 3DPX accession code (e.g., 3dpx-######)

##### \* Contributors to the NIH 3D Print Exchange can specify [license types](http://3dprint.nih.gov/about/site-policies/licensing) for their models. The default for models is “public domain” which imposes no restrictions on reuse. At this time, these are the only models available through the API.

## Rate Limits
The 3DPX API relies on [api.data.gov](http://api.data.gov/)’s services for rate limiting and metrics tracking. The default rate limit of 1000 requests per hour applies to all 3DPX API users. You may [contact us](http://3dprint.nih.gov/contact) if you require a higher request rate.

## Examples
Return all available fields (see “[Field Reference](http://niaid.github.io/3dpx_api/field_reference/)” section) for the [Peppytides foldable model of the polypeptide chain](http://3dprint.nih.gov/discover/3dpx-000914), which has the accession code ‘3dpx-000914’. Please note that these examples use the "DEMO" API Key for api.data.gov. This key is for demo purposes only and imposes high rate limits. Click [here](http://niaid.github.io/3dpx_api/api_key/) to register for a free and full-featured API Key for use in your application(s).

* XML: [http://api.data.gov/nih/3dprint/model/1.0/model_single?model_id=000914&api_key=DEMO_KEY](http://api.data.gov/nih/3dprint/model/1.0/model_single?model_id=000914&api_key=DEMO_KEY)
* JSON: [http://api.data.gov/nih/3dprint/model/1.0/model_single.json?model_id=000914&api_key=DEMO_KEY](http://api.data.gov/nih/3dprint/model/1.0/model_single.json?model_id=000914&api_key=DEMO_KEY)

