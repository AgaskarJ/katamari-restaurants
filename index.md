---
layout: default
bodyClass: page-home
title: Lost Restaurants of Cambridge and Somerville
displayTitle: " "
excerpt: >
  A summary of the running loss of local restaurants to deep-pocketed private 
  equity, private investment and national chains.
style: |
  .blocktable {
    table-layout: fixed;
  }
  .blocktable thead th {
    text-align: left;
  }
---

# Lost Restaurants of Cambridge and Somerville

_A summary of the running loss of local restaurants._

When $2T-$6T of freshly-printed government-guaranteed low-cost credit goes to
deep-pocketed private investment firms, transnational corporations, big banks,
investors and monopolists, we'll quickly see the biggest loss of local
restaurants and the rise of national chains.

This will fundamentally reshape the terrain of independently run restaurants in
the US and around the globe. The Urban America we know, of heterogeneous small
restaurants would look very different after this pandemic is over&mdash;a
homogeneous space optimized for massive corporations, and reducing local
autonomy and diversity.

## The List

<table class="blocktable">
  <thead>
    <th scope="column" width="40%">Name / Date</th> 
    <th scope="column" width="40%">Notes</th>
    <th scope="column" width="20%">
      <abbr title="Replaced by">Replacement</abbr>
    </th>
  </thead>
  <tbody>
   {% for item in site.data.companies %}
     {% assign key = item[0] %}
     {% include company-row.html key=key %}
   {% endfor %}
  </tbody>
</table>
