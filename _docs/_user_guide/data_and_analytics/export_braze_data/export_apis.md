---
nav_title: Export APIs
page_order: 8
description: "Braze's export APIs allow you to programmatically export a JSON file of Dashboard data."

---

# Export APIs

Braze's export APIs allow you to programmatically export a JSON file of Dashboard data. Our [documentation page on export APIs][24] contains a list of data that you can access, as well as instructions and sample code for the export.

There are a few reasons why you would prefer this method over exporting a CSV directly from the Dashboard:

 - Your file is very large. From our Dashboard, you can export a CSV with at most 500,000 rows. If you're exporting data on a segment with over 500,000 users, you'll need to use our export API, which places no limit on how much you can export.
 -  You wish to interact with the data programmatically.

[24]: {{site.baseurl}}/developer_guide/rest_api/export/#export
