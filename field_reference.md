---
layout: default 
title: Field Reference
permalink: /field_reference/
---

## Field Reference

### Data returned by the 3DPX API

<table class="table">
  <thead>
    <tr>
      <th class="th">Field name</th>
      <th class="th">Description</th>
      <th class="th">Data type</th>
    </tr>
  </thead>
  <tbody>

  {% for field_refs_for_3dpx_read_api in site.data.field_refs_for_3dpx_read_apis %}
  <tr>
    <td class="td">{{ field_refs_for_3dpx_read_api.field_name }}</td>
    <td class="td">{{ field_refs_for_3dpx_read_api.description }}</td>
    <td class="td">{{ field_refs_for_3dpx_read_api.data_type }}</td>    
  </tr>
  {% endfor %}
  </tbody>
</table>

<!---
#### II. Model Metadata Fields for 3DPX "Write" APIs
The following fields are required for proper pipeline processing and/or organization within the repository, and should be included in any API-based model submissions.

<table>
  <thead>
    <tr>
      <th class="th">Label</th>
      <th class="th">Field Name</th>
      <th class="th">Field Type</th>
    </tr>
  </thead>
  <tbody>
  {% for field_refs_for_3dpx_write_api in site.data.field_refs_for_3dpx_write_apis %}
  <tr>
    <td class="td">{{ field_refs_for_3dpx_write_api.label }}</td>
    <td class="td">{{ field_refs_for_3dpx_write_api.field_name }}</td>
    <td class="td">{{ field_refs_for_3dpx_write_api.field_type }}</td>    
  </tr>
  {% endfor %}
  </tbody>
</table>
-->