---
name: GC Articles Publishing User Story Template
about: Template for creating new User Stories for Notify backlog
title: 'Give your user story a simple, clear title'
labels: ''
assignees: ''

---
## Description
As a (user), I need to be able to do (X) so that I can achieve (Y) outcome. 

WHY are we building?
WHAT are we building?
VALUE created by our solution

## Documentation and Artifacts
Good docs, figma mockups, ADRs, screenshots etc.

## Acceptance Criteria
Given some context, when (X) action occurs, then (Y) outcome is achieved 

- [ ] Update the status of related findings, insights, and hypotheses on the Research Airtable
- [ ] Once change/fix/feature is implemented, link relevant Airtable records to design artifacts (Figma)

* A11y
* Bilingualism
* Measuring success and metrics

## Related [Research Airtable](https://airtable.com/appWwAmHwDLtpIyko/tbl38n7ofWYBuezFc/viwQUX3tUxbMxYS7C?blocks=hide) records
- (find stuff yourself)

## QA Steps
- [ ] Tested in a realistic production scenario

## GC Articles Publish checklist
### Update to a public page
- [] Supporting feature is released and unflagged
- [] Page content is translated
- [] Update to a public page with new slug
- [] Supporting feature is released and unflagged
- [] Update slug
- [] Page content and slug is translated
- [] Create other language and link translations
- [] Ping devs to avoid broken links (new slugs)
- [] Ping devs to update WAF rules
- [] Ping devs to add slug to the UI test suite
### New public page
- [] Supporting feature is released and unflagged
- [] Create slug
- [] Page content and slug is translated
- [] Create other language and link translations
- [] Ping devs to avoid broken links (new slug)
- [] Ping devs to update WAF rules
- [] Ping devs to add slug to the UI test suite
### Add an article to the new features page
- [] Supporting feature is released and unflagged
- [] Content is translated
- [] Create other article in the other language
### Add an article to the status page
- [] Content is translated
- [] Create other article in the other language
### Archiving a policy page (Combination of Update and New pages)
- [] Consult Policy or PM to validate archiving
- [] Content is translated
- [] Create slug for the archived version
- [] Archived slug is translated
- [] Create other language and link translations
- [] Ping devs to avoid broken links (new slug)
- [] Ping devs to update WAF rules
- [] Ping devs to add slug to the UI test suite
### Previewing content on a new page (recommended if working on a complex layout)
- [] Set the slug to ‘_preview_’ + your choice of slug
### Post publishing checklist
- [] On staging: Clear the cache through GC Notify's admin panel
- [] On staging: Check links, images and language toggle
- [] Ping someone with the staging links to the updated pages for QA
- [] On production: Clear the cache through GC Notify's admin panel

