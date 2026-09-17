```markdown
# Micro-WMS — Warehouse Management System

## Overview

Micro-WMS is an Excel and VBA-based warehouse management solution designed to simplify inventory handling and improve warehouse movement efficiency.

The system combines inventory tracking, storage allocation, warehouse mapping, and picking-route optimization into a single workbook.

## Key Features

- Inventory and transaction tracking
- Automated warehouse bin allocation
- PICK and PUTAWAY operations
- Bin capacity validation
- Warehouse layout visualization
- Multi-location order handling
- Picking route generation
- Inventory status tracking

## How It Works

The user enters an SKU, quantity, and warehouse operation through the input interface.

The system then:

1. Validates the requested operation.
2. Identifies a suitable storage location.
3. Updates inventory records.
4. Stores the transaction history.
5. Determines the required warehouse route.
6. Displays the movement path on the warehouse map.

## Optimization

The project uses route optimization techniques to reduce unnecessary warehouse movement.

### A* Pathfinding

A* is used to determine a valid path between warehouse locations while considering obstacles in the warehouse layout.

### Nearest Neighbor

Nearest Neighbor is used to create an initial sequence for visiting multiple warehouse locations.

### 2-OPT

The 2-OPT approach improves the initial route by testing alternative combinations of warehouse stops and reducing unnecessary travel.

## Warehouse Operations

The system supports common warehouse activities such as:

- Inventory placement
- Stock retrieval
- Bin allocation
- Order picking
- Inventory movement
- Warehouse route planning

## Technology Used

- Microsoft Excel
- VBA
- AutoCAD
- A* Pathfinding
- Route Optimization

## Applications

This type of system can support:

- Warehouse inventory management
- Storage allocation
- Order picking
- Warehouse planning
- Inventory movement tracking
- Operational process improvement

## Future Improvements

- Barcode-based inventory updates
- Real-time stock synchronization
- Warehouse performance dashboards
- Order-priority handling
- SQL database integration
- Automated operational reports

## Conclusion

Micro-WMS demonstrates how spreadsheet automation and optimization techniques can be combined to support warehouse planning, inventory management, and efficient material movement.
```
