
## **Project Overview**

This document outlines the design and implementation of **intelligent GPS tracking collars**, specifically tailored for two use cases: **ElderGPS** for elderly individuals and **AnimaGPS** for animals. The system ensures safety and tracking reliability, using advanced GPS and GSM modules integrated into durable and ergonomic collars.

The collars are designed by **GeoLink Technologies**, a company specializing in localization technologies. The project incorporates the complete lifecycle from design to production, with components defined and processes implemented using SAP for efficient manufacturing and tracking.

---

## **Features**

1. **ElderGPS**:
   - Tracks the real-time location of elderly individuals, particularly those with Alzheimer's.
   - Includes an SOS button for emergency alerts to predefined contacts.
   - Lightweight and comfortable design for extended use.

2. **AnimaGPS**:
   - Robust GPS tracking for medium to large animals.
   - Features a 30-day battery life, suitable for outdoor use.
   - Waterproof and shock-resistant casing for durability.

3. **Technological Integration**:
   - **GPS Module**: Provides precise tracking with a ±5m accuracy.
   - **GSM Module**: Enables connectivity for remote monitoring via a mobile application.
   - Smart embedded systems for real-time processing and communication.

4. **Manufacturing Workflow**:
   - SAP is used for managing materials, scheduling production, and monitoring inventory.
   - Modular production process with detailed component breakdowns.

---

## **System Composition**

### **Hardware Components**
- **GPS Module**: NEO-6M GPS with EEPROM for data storage.
- **GSM Module**: EC25 GSM for connectivity.
- **Microcontroller**: STM32 F407 for data processing.
- **Power**: Li-Po batteries (300mAh and 500mAh options).
- **Casing**: Plastic ABS (standard and reinforced).
- **Straps**: High-quality leather straps tailored for comfort.

### **Manufacturing Facilities**
- Modern assembly lines for electronic components.
- Dedicated molding and finishing stations for casings and straps.
- Quality assurance labs for testing final products.

---

## **Software Integration**

### **SAP Integration**
- **Material Management**:
  - Components like leather, ABS plastic, and electronic modules are tracked through SAP's MM module.
  - Suppliers include PCBWay for PCBs and U-Blox for GPS modules.

- **BOM Management**:
  - Bill of Materials (BOM) defined and visualized using SAP's CS01 and CS03 transactions.
  - Links components to their respective manufacturing processes.

- **Production Planning**:
  - SAP's MC89 and MD02 transactions used for demand forecasting and net requirement calculations.
  - Real-time tracking of work orders and inventory with COOIS and MB52.

---

## **Instructions for Use**

### **ElderGPS**
1. Wear the collar around the neck.
2. Press the SOS button in emergencies to send an alert.
3. Monitor location via the mobile application.

### **AnimaGPS**
1. Secure the collar on the animal using the adjustable leather strap.
2. Recharge the battery after 30 days of usage.
3. Track movements and set geofences using the app.

---

## **Production Details**

### **Material Calculations**
1. **Leather Usage**:
   - ElderGPS: A 150cm x 50cm leather sheet produces approximately 10 straps.
   - AnimaGPS: A 200cm x 150cm sheet yields up to 60 straps.

2. **Plastic Casings**:
   - ElderGPS casings require 100g of ABS per unit, enabling 10 casings per kg.
   - AnimaGPS casings use 50g of ABS per unit, allowing 20 casings per kg.

3. **PCB Production**:
   - A 40cm x 20cm PCB sheet provides 10 PCBs through precise cutting.

### **Workflow**
- Automated and manual assembly stations.
- Post-assembly testing for GPS and GSM modules.
- Final packaging for distribution.

---

## **Future Enhancements**
- Integration of solar charging for extended battery life.
- Enhanced connectivity using 5G modules.
- Development of lightweight materials for increased comfort.

---

## **Contact**
For further details, visit **GeoLink Technologies** or contact their support team.

Enjoy the enhanced safety and reliability of your GPS tracking collar system! 🚀
