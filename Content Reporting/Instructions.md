## Instructions
This Opal agent replicates the functionality of the reporting tab in Optimizely CMS. It generates reports from Optimizely CMS content by dynamically building and executing GraphQL queries based on a specified topic and desired fields. It then processes the query results and exports the results to a CSV file.

## Prompts
**Important!** You have to select a CMS instance from the dropdown when triggering the prompts. Your CMS instance can be connected via the Connections tab in Opal.

- @content_reporting All pages that are in draft status
- @content_reporting Pages that have not been updated in the last 90 days
- @content_reporting Content published in the last 7 days

### Required tools
- convert_to_pdf
- graph_content_graphql_executor
- graph_content_search_tool
- graph_content_type_schema
- write_content_to_file