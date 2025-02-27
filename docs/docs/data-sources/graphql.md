---
sidebar_position: 9
---

# GraphQL


ToolJet can connect to GraphQL endpoints to execute queries and mutations.

## Connection

To add a new GraphQL datasource, click the `+` button on  data sources panel at the bottom-left corner of the app builder and then select GraphQL from the modal that pops up.

ToolJet requires the following to connect to a GraphQL datasource.

- URL of the GraphQL endpoint

The following optional parameters are also supported:

   | Type         | Description |
   | -----------  | ----------- |
   | URL params   | Additional query string parameters|
   | headers      | Any headers the GraphQL source requires|



<img class="screenshot-full" src="/img/datasource-reference/graphql/add-source.gif" alt="ToolJet - GraphQL connection" height="420"/>

Click on the 'Save' button to save the data source.

## Querying GraphQL
Click on `+` button of the query manager at the bottom panel of the editor and select the GraphQL endpoint added in the previous step as the  data source. 

<img class="screenshot-full" src="/img/datasource-reference/graphql-query.png" alt="ToolJet - GraphQL connection" height="420"/>

Click on the 'run' button to run the query. NOTE: Query should be saved before running.

:::tip
Query results can be transformed using transformations. Read our transformations documentation to see how: [link](/docs/tutorial/transformations)
:::