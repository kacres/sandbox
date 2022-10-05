---
name: Engineering Artifacts
about: This template provides a space to keep track of your solutions to the tasks
  and challenges presented during RnD Discovery
title: ''
labels: ''
assignees: ''

---

## Instructions:
1. After a task is completed, mark it as done using the checklist below.
2. For each task, submit your artifact as a new comment.
3. In the comment, include the title of each task (the text in bold in the checklist)

## Task Checklist:
- [ ] **My first PR** - provide a link to your first PR
- [ ] **GSD and the Champion** - One role of GSD is the champion. Looking at various projects, you may have noticed that the champion can belong to any craft (ie Data, Engineering, Product or UX). *For a particular project, how is the ‘best champion’ for the job chosen?* 
- [ ] **Spin Challenge**
  * Use spin to create a development environment for web
  * View your development environment in your browser and navigate to the Orders > Abandoned checkouts page
  * Use VS Code to change the title or the description. A sample change is shown below.
    <br><img src="/images/abandoned-cart.png?raw=true" alt="abandoned cart" width="200"/>
    <!---![abandoned_cart](/images/abandoned-cart.png?raw=true)--->
  * *Post a screenshot of your change in the comment.*
- [ ] **GraphQL and Services Internal**
  * There is a Shopify store called ODR Training run by kyle.acres@shopify.com. In that store there is a product with an id: 6539208163350.
  * Use the graphiQL interface in services internal to write a graphQL query to find the title of this product.
  * *Post the query you created and the title of the product*
- [ ] **Consuming the Admin API**
  * Headless commerce (the ability to create customized storefronts that utilize Shopify’s backend) is made possible with Hydrogen, a React-based framework.  
  Challenge:
    1. Navigate to hydrogen.new where you will see three featured collections (Figure 1).
    2. Modify the GraphQL query to retrieve only the first 2 collections and also retrieve the description
    3. Adjust the FeaturedCollections to include the description using a Text component
