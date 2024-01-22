# SupplyCo Electronics Supply Chain Management Project

## Background
The SupplyCo Electronics Supply Chain Management project aimed to enhance business operations by implementing an efficient database system. The initiative addressed challenges in inventory management, order processing, manufacturing processes, and logistics.

## Problem Statement
The existing system lacked integration and faced inefficiencies in various supply chain stages. Manual processes resulted in delays, errors, and difficulties in tracking inventory. The need for a centralized database system to streamline operations was imperative.

## Database Requirements
The project required a robust database system to manage inventory, orders, manufacturing processes, and employee information. Data integrity, relational associations, and efficient querying were crucial aspects. PostgreSQL was chosen as the database management system.

### Inventory Management:

- Track raw materials, work-in-progress, and finished goods with attributes such as SKU, description, quantity, cost, supplier details, and manufacturing date.

### Supplier Management:

- Maintain a supplier database for raw materials, including supplier name, contact information, address, and a list of supplied materials.

### Manufacturing Process:

- Record manufacturing process details for electronic components, capturing information like production date, batch number, and raw materials used.

### Order Management:

- Manage customer orders, tracking their status (e.g., pending, processing, shipped), and include customer information, order date, delivery address, and order details.

### Shipment and Logistics:

- Monitor the shipment process, including shipping carriers, tracking numbers, delivery status, shipping date, expected delivery date, and transportation details.

### Employee Management:

- Maintain employee records with details like roles, contact information, and department information. Record employee involvement in manufacturing and logistics processes.

### Quality Control:

- Implement a quality control system to track the quality of manufactured components, including attributes like inspection date, quality check results, and any rework or rejection details.

## Deliverables

1. **Comprehensive Database Design:**
   - Develop a thorough database design that encompasses inventory management, order processing, manufacturing, and employee management. Consider all relevant entities, attributes, and relationships.
   
2. **Dockerized Environment:**
   - Implement a Dockerized environment to facilitate seamless deployment and scalability. Ensure the environment is well-configured for the efficient operation of the database.

3. **Entity-Relationship Diagram (ERD):**
   - Provide a clear and visually appealing ERD that illustrates the entities and their relationships within the system. Use appropriate notations to enhance comprehension.

4. **Logical Schema:**
   - Define the database schema, including tables, fields, and relationships. Use SQL or any chosen database language to articulate the logical structure of the database.

5. **Documentation on dbdocs.io:**
   - Make documentation available on dbdocs.io for convenient reference and enhanced understanding of the database structure. Ensure the documentation is detailed and accessible.

6. **Configuration for PostgreSQL Administration (pgAdmin):**
   - Set up configurations for the PostgreSQL administration tool, pgAdmin. This should include user roles, permissions, and any necessary settings for efficient database management.

7. **Sample Queries:**
   - Propose a set of sample queries that showcase the functionality of the database. These queries should cover common use cases and demonstrate the versatility of the database.

8. **Normalization Techniques:**
   - Apply normalization techniques to the database structure to ensure it is well-structured, normalized, and avoids redundancy. Document the normalization process for clarity.

9. **Indexing Strategy:**
   - Recommend and implement an effective indexing strategy to optimize query performance. Explain the rationale behind the chosen indexing strategy and how it aligns with the database's usage patterns.

These deliverables collectively aim to provide a comprehensive, well-documented, and optimized database solution that meets the specified requirements.

## DATABASE DESIGN PROCESS 
### Phase I: Requirements Collection and Analysis
- Interviewed and consulted with database users to understand data requirements.
- Identified key entities and relationships, laying the foundation for the conceptual design.

### Phase II: Conceptual Design
- Formulated a comprehensive E-R diagram representing the identified entities and relationships.

### Phase III: Logical Design (Data model mapping)
- Translated the conceptual design into a logical database schema.
- Specified entities, relationships, attributes, primary keys, and foreign keys.

### Phase IV: Physical Design (Internal Schema)
- Transformed the logical database schema into a physical database.
- Created tables, specified columns, defined data types, and implemented constraints and keys.

### Phase V: Usage and Setup
- Employed Docker and Docker Compose for a standardized environment.
- Offered detailed setup instructions in the readme, including links to online documentation and ERD images.

For detailed information, refer to the [online documentation](#) on dbdocs.io.

## Tools Used
- Docker and Docker Compose for containerization.
- PostgreSQL as the database management system.
- pgAdmin for PostgreSQL administration.
- dbdiagrams.io
- dbdocs.io
- draw.io
- mermaid.js.org

## Setup
1. Clone the repository.
2. Navigate to the project directory.
3. Run `docker-compose up -d` to start the containers.
4. Access pgAdmin on `localhost:pgadmin_port` and manage PostgreSQL.
5. Explore the database schema through dbdocs.io documentation.

## Ports
- PostgreSQL: `localhost:postgresql_port`
- pgAdmin: `localhost:pgadmin_port`

Explore the power of streamlined supply chain management with the SupplyCo Electronics project!
