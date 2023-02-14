# Natural Language Processing with Python for SEOs

We are going to extract useful facts automatically from SEJ XML sitemaps.

In order to do this and keep things simple and fast, we will pull article headlines from the URLs in the XML sitemaps.

We will extract entities of interest and their relationships from the headlines.

Finally, we will build a powerful knowledge graph and visualize the most popular relationships.

Here is the technical plan:

1. We will fetch all SEJ XML sitemaps
2. We will parse the URLs to extract the headlines in their slugs 
3. We will extract entity pairs from the headlines 
4. We will extract corresponding relationships
5. We will build a knowledge graph and a simple form to visualize specific relationships
