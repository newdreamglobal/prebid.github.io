---
layout: bidder
title: 360PlayVid
description: Prebid 360PlayVid Bidder Adapter
biddercode: 360playvid
gpp_sids: usstate_all
gvl_id: none
tcfeu_supported: true
usp_supported: true
coppa_supported: true
schain_supported: true
deals_supported: false
floors_supported: true
fpd_supported: false
ortb_blocking_supported: false
media_types: banner, video, native
multiformat_supported: will-bid-on-one
userIds: all
pbjs: true
pbs: false
pbs_app_supported: true
safeframes_ok: true
sidebarType: 1
---

### Bid Params

{: .table .table-bordered .table-striped }
| Name          | Scope    | Description  | Example                         | Type       |
|---------------|----------|--------------|---------------------------------|------------|
| `placementId` | optional | Placement Id | `'0'`                           | `'string'` |
| `endpointId`  | optional | Endpoint Id  | `'0'`                           | `'string'` |

### Note

For the prebid server and prebid.js you only need to use one parameter: either placementId or endpointId
