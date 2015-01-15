---
layout: page
title: Field Reference for 3DPX APIs
---
### I. Model Metadata Fields for 3DPX "Read" API Calls

<table>
  <thead>
    <tr>
      <th>Field name</th>
      <th>Description</th>
      <th>Data Type</th>
    </tr>
  </thead>
  <tbody>

  {% for field_refs_for_3dpx_read_api in site.data.field_refs_for_3dpx_read_apis %}
  <tr>
    <td>{{ field_refs_for_3dpx_read_api.field_name }}</td>
    <td>{{ field_refs_for_3dpx_read_api.description }}</td>
    <td>{{ field_refs_for_3dpx_read_api.data_type }}</td>    
  </tr>
  {% endfor %}
  </tbody>
</table>

### II. Model Metadata Fields for 3DPX "Write" APIs
The following fields are required for proper pipeline processing and/or organization within the repository, and should be included in any API-based model submissions.

<table>
  <thead>
    <tr>
      <th>Label</th>
      <th>Field Name</th>
      <th>Field Type</th>
    </tr>
  </thead>
  <tbody>
  {% for field_refs_for_3dpx_write_api in site.data.field_refs_for_3dpx_write_apis %}
  <tr>
    <td>{{ field_refs_for_3dpx_write_api.label }}</td>
    <td>{{ field_refs_for_3dpx_write_api.field_name }}</td>
    <td>{{ field_refs_for_3dpx_write_api.field_type }}</td>    
  </tr>
  {% endfor %}
  </tbody>
</table>
