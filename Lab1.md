# Cloud Migration

**Company Name:** Bankingly

**Company's motivators of migration to the cloud:**
Bankingly provides web services and mobile applications to microfinance institutions in rural Latin America with the goal of promoting digital inclusion. Bankingly is migrating into the cloud because of:
- Scalability
- Cost Efficiency
- Security
- Global reach

### Questions to ask:
- Which type of database are you using currently?
- How is the database structured, and what is the size of the data?
- What type of security measures do you want in Azure?
- Are there any specific requirements you want to add during this migration?

## RACI Matrix:

| Task                    | Project Manager | CIO | Cloud Engineers | IT Team | QA Team | Stakeholders | Cloud Provider (Azure) |
|--------------------------|----------------|-----|----------------|---------|---------|--------------|-----------------------|
| **Migration Planning**    | R              | A   | C              | C       | -       | I             | -                   |
| **Infrastructure Setup**  | A              | -   | R              | C       | -       | I             | C                      |
| **Data Migration**        | A              | -   | -               | R       | -       | I            | -                      |
| **Testing & Validation**  | A              | -   |                | C       | R       | I            | -                     |
| **Go-Live**               | -              | A   | R              | C       | -       | I             | -                    |

**RACI:** Responsible, Accountable, Consulted, and Informed

## Most likely migration approach:
There are six types of R's for successful cloud migration:
1. **Rehost (Lift-and-Shift)**
2. **Replatform**
3. **Repurchase (Drop-and-Shop)**
4. **Refactor**
5. **Retain**
6. **Retire**

## Schedule for the migration process:

| Phase                       | Timeline       |
|-----------------------------|----------------|
| **Planning and Assessment**  | 1-2 Weeks      |
| **Migration Strategy and Design** | 2-3 Weeks  |
| **Application and Data Migration** | 2-3 Weeks |
| **Testing and Optimization** | 4-6 Weeks      |
| **Training and Documentation** | 1-2 Weeks    |
| **Go-Live and Monitoring**   | 2-3 Weeks      |

## Decision criteria for Bankingly:
- **Scalability:** The ability to increase the service as the demand grows, especially in rural and underserved markets.
- **Cost Efficiency:** Azure has a "Pay as you go" feature to ensure cost efficiency.
- **Performance:** High performance is mandatory for Bankingly, with low latency rates for customers accessing services from rural areas.
- **Minimal Downtime:** During the migration, it is important that some essential services remain available.
