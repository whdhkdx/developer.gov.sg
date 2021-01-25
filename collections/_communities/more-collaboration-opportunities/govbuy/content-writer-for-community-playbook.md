---
title: Content Writer for Community Playbook
layout: layout-page-sidenav
---

{% assign jobDetails = site.data.gigs | where: "title", page.title | first %}

{% unless jobDetails.open %}
**The bidding period for this job is over**
{% else %}
<a href="{{ jobDetails.bid_link }}" class="sgds-button is-primary">
  Submit your bid here
</a>
{% endunless %}

### The task

GovTech's community engagement team is looking for a content writer to put together our first Community Playbook. The Playbook will be a reference for others keen to start their own communities. It will contain our community engagement journey, tips on holding events and on growing your community.

### Deliverables

Community playbook (1500 words) that is light in tone and engaging to read. Most of the content will be from interviews conducted with the teams. A first draft is expected by 14 Feb 2021 after the successful candidate is confirmed on 1 Feb 2021. The job is to be completed by 26 Feb.

### Skills required

{% for skill in jobDetails.skills %}
- {{ skill }}
{% endfor %}

### Offer

{% include govbuy-offer-table.md 
  offer=jobDetails.offer duration=jobDetails.duration
  posted=jobDetails.posted closing=jobDetails.closing %}

### Evaluation methods

**For bidding of job**

- Cover letter
- Portfolio consisting of at least 3 published articles

**For acceptance of deliverables**

- Content and standard of first draft must detail community engagement journey and growth, profiles of team members, tips/SOPs on holding events and tips on growing communities

### The team

International and Community Development, Technology Management Office, GovTech
