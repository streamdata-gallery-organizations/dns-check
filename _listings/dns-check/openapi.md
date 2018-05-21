---
swagger: "2.0"
x-collection-name: DNS Check
x-complete: 1
info:
  title: DNS Record Group Monitoring API
  description: a-dns-record-group-is-a-logical-collection-of-dns-records-dns-record-groups-can-have-a-onetoone-correlation-with-zone-files-but-other-types-of-groupings-are-possible-as-well-such-as-grouping-by-service-or-customer-see-the-dns-record-groups-page-for-more-details-the-dns-check-api-is-used-to-request-data-for-either-a-specific-record-group-or-all-dns-record-groups-owned-by-your-account
  version: v1
host: www.dnscheck.co
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /groups/:group_uuid:
    get:
      summary: Check Group
      description: The DNS Check API is used to request data for either a specific
        record group, or all DNS record groups owned by your account.
      operationId: getGroups
      x-api-path-slug: groupsgroup-uuid-get
      parameters:
      - in: query
        name: api_key
        description: The secret key thats used to authenticate the connecting application
        type: string
        format: string
      - in: query
        name: group_uuid
        description: The UUID of the DNS record group
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Groups
---