# SupplyCo Electronics Supply Chain Management Project

## Background
The SupplyCo Electronics Supply Chain Management project aimed to enhance business operations by implementing an efficient database system. The initiative addressed challenges in inventory management, order processing, manufacturing processes, and logistics.

## Problem Statement
The existing system lacked integration and faced inefficiencies in various supply chain stages. Manual processes resulted in delays, errors, and difficulties in tracking inventory. The need for a centralized database system to streamline operations was imperative.

## Database Requirements
The project required a robust database system to manage inventory, orders, manufacturing processes, and employee information. Data integrity, relational associations, and efficient querying were crucial aspects. PostgreSQL was chosen as the database management system.

## Deliverables
1. Comprehensive database design addressing inventory, orders, manufacturing, and employee management.
2. Dockerized environment for easy deployment and scalability.
3. ERD (Entity-Relationship Diagram) providing a visual representation of the database structure.
4. Logical schema detailing the entities, attributes, and relationships.
5. Documentation available on dbdocs.io for reference and ease of understanding.
6. Configurations for PostgreSQL administration tool, pgAdmin.

## Flowchart Process
### Phase I: Requirements Collection and Analysis
- Interviewed and consulted with database users to understand data requirements.
- Developed an E-R diagram with necessary entities and relationships.

### Phase II: Logical Design (Data model mapping)
- Converted E-R diagram to a logical database schema.
- Specified entities, relationships, attributes, primary keys, and foreign keys.

### Phase III: Physical Design (Internal Schema)
- Converted logical database schema to physical database.
- Created tables, specified columns, data types, constraints, and keys.

### Phase IV: Usage and Setup
- Utilized Docker and Docker Compose for a standardized environment.
- Provided a readme for project setup, including links to online documentation and ERD images.

For detailed information, refer to the [online documentation](#) on dbdocs.io.

## Tools Used
- Docker and Docker Compose for containerization.
- PostgreSQL as the database management system.
- pgAdmin for PostgreSQL administration.

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
