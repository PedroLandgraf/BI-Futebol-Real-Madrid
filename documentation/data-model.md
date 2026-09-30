# Data Model

The Power BI solution uses a structured analytical data model designed to separate dimensions from transactional and analytical facts.

## Main Components

### Dimensions

Examples include:

- Date
- Match
- Sector
- Player
- Player Photo
- Team
- Time-related dimensions

### Fact Tables

The model includes fact structures supporting:

- Match attendance
- Ticket sales
- Revenue
- Player information
- Membership information

## Modeling Approach

The model was structured to support:

- Reusable DAX measures
- Cross-filtering
- Time intelligence
- Player-level analysis
- Match-level analysis
- Sector-level analysis
- Dynamic visual interactions

The model separates descriptive attributes from analytical transactions to improve maintainability and reporting flexibility.
