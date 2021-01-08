# pencile_backend
The goal of this project is to store and create an index over question objects in MongoDB, and write a NodeJS + Express based server that exposes a RESTful API to query the index and return questions that match the query. Each question will be annotated with one or more annotations. An annotation is defined as a topic that can come from a topic tree. An example topic tree is shown below.