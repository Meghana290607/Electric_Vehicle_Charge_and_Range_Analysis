# Entity Relationship (ER) Diagram

## Overview

The ER Diagram represents the relationships between the entities used in the Electric Vehicle database.

---

## Entities

### Manufacturer

Attributes:

- Manufacturer_ID
- Manufacturer_Name
- Country

---

### Electric Vehicle

Attributes:

- Vehicle_ID
- Brand
- Model
- Battery Capacity
- Driving Range
- Charging Time
- Top Speed
- Price
- Body Style
- Powertrain

---

### Battery

Attributes:

- Battery_ID
- Capacity
- Battery Type
- Warranty

---

### Charging Station

Attributes:

- Station_ID
- Station_Name
- State
- City
- Charging Type

---

## Relationships

- One manufacturer produces many electric vehicles.
- Each electric vehicle uses one battery.
- Charging stations support multiple electric vehicles.
- Vehicle information is visualized using Tableau.

---

## Benefits

- Reduces redundancy
- Maintains consistency
- Improves query performance
- Supports future expansion
