# An E-Commerce Recommendation System
---
## Project In Progress ...
---

## Overview of Recommendation Systems
Recommendation systems are advanced data-driven tools designed to predict and suggest items of interest to users based on their past behaviours and preferences. They play a crucial role in enhancing user experiences on e-commerce platforms, streaming services, social media, and more. These systems leverage algorithms such as collaborative filtering, content-based filtering, and hybrid approaches to generate personalised recommendations. By analysing user interactions, purchase histories, and item attributes, recommendation systems can increase user engagement, boost sales, and improve customer satisfaction.

In e-commerce, recommendation systems help users discover products they might not have found otherwise, offering tailored suggestions based on browsing history, cart behaviour, and purchase patterns. They also drive business value by enhancing conversion rates and optimising the shopping experience.


## Problem Statement
The goal of this project is to develop a robust recommendation system for a real-world e-commerce dataset, focusing on implicit feedback derived from user behaviour. The dataset includes three key files: behavioural data (events.csv), item properties (item_properties.csv), and a category hierarchy (category_tree.csv). The behavioural data captures over 2.7 million events, including views, add-to-carts, and transactions from approximately 1.4 million unique visitors over a 4.5-month period. The item properties file provides dynamic attributes of over 417,000 unique items, while the category tree outlines parent-child relationships between product categories.

The primary objectives of this project include:

- To develop an algorithm to predict item properties for "addtocart" events using data from "view" events.
- Identify and filter out abnormal user behaviour to enhance the recommendation system's efficiency.
