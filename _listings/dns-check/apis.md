---
name: DNS Check
x-slug: dns-check
description: Monitor DNS records. Request DNS updates by sharing reports that show
  the pass/fail status of each record. Troubleshoot DNS issues. DNS records are automatically
  re-checked, and reports updated. DNS records can be imported from a zone file, or
  added in...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18972-dns-check.jpg
x-kinRank: "8"
x-alexaRank: "3315601"
tags: DNS Check
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/dns-check/master/_listings/dns-check/apis.md
specificationVersion: "0.14"
apis:
- name: DNS Record Group Monitoring API Check Group
  x-api-slug: dns-record-group-monitoring-api
  description: The DNS Check API is used to request data for either a specific record
    group, or all DNS record groups owned by your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18972-dns-check.jpg
  humanURL: https://www.dnscheck.co/
  baseURL: https://www.dnscheck.co//api/v1//groups/:group_uuid
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/dns-check/master/_listings/dns-check/groupsgroup-uuid-get-openapi.md
- name: DNS Record Group Monitoring API
  x-api-slug: dns-record-group-monitoring-api
  description: A DNS record group is a logical collection of DNS records. DNS record
    groups can have a one-to-one correlation with zone files, but other types of groupings
    are possible as well, such as grouping by service or customer. See the DNS record
    groups page for more details. The DNS Check API is used to request data for either
    a specific record group, or all DNS record groups owned by your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18972-dns-check.jpg
  humanURL: https://www.dnscheck.co/
  baseURL: https://www.dnscheck.co//api/v1
  tags: DNS Check
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/dns-check/master/_listings/dns-check/openapi.md
x-common:
- type: x-developer
  url: https://www.dnscheck.co/documentation
- type: x-pricing
  url: https://www.dnscheck.co/pricing
- type: x-twitter
  url: https://twitter.com/dns_check
- type: x-website
  url: https://www.dnscheck.co/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---