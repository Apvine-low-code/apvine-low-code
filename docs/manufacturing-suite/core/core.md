# Core – Manufacturing Suite

The **Core** serves as the foundation of the manufacturing suite. It manages centralized master data that is critical to the operation and integration of all other modules. This ensures consistency, accuracy, and integrity of key operational data.

## Key objects

The Core Module provides master data management for the following entities:

- **Location management**
- **Equipment management**
- **Material management**
- **Shift management**
- **Configuration & settings**

---

## 1. Location management

Locations represent physical or logical areas within the production environment, such as production lines, storage areas, or quality labs.

---

## 2. Equipment management

**Equipment** entities define the machines, tools, or systems used in manufacturing. **Equipment Classes** group similar types of equipment for categorization and configuration purposes.

---

## 3. Material management

**Material Classes** are used to define groups of materials that share common characteristics or behaviors in the system.
**Materials** define the material codes that are known within the company. 
**Material batch** define a batch of a specific materials



## Integration

The **Core** is designed to integrate seamlessly with other modules in the manufacturing suite, including:

- Order cockpit
- Quality Management
- Downtimes
- ...

All modules rely on the master data maintained in the Core Module to function accurately and consistently.This to have a single version of the truth. 


