### Relationships in the pet adoption agency schema:
---
- Animals and Species have a one-to-many relationship, where each animal belongs to a specific species, and each species can have multiple animals. (1 Species: N Animals)

- Animals and Adoptions have a one-to-one relationship, where each animal can be adopted once, and each adoption is associated with one animal. (1 Animal: 1 Adoption)

- Owners and Adoptions have a one-to-many relationships, where each owner can adopt multiple animals, and each adoption is associated with one owner. (1 Owner: N Adoptions)