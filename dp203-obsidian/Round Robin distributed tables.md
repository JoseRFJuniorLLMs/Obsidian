---
tags:
  - AzureSynapse
---
**Advantages:**

1. **Load Balancing:** Round Robin evenly distributes rows among the nodes, ensuring a balanced load.
2. **Simplicity:** It's simple to implement and understand.

**Disadvantages:**

1. **Inefficient for Certain Queries:** May result in inefficient performance for queries that need to access many consecutive rows, as the rows may be distributed across different nodes.
2. **Doesn’t Consider Data Distribution:** Doesn't take into account underlying data distribution and can result in imbalances if rows have different sizes.