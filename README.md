# GeoFare

A mobile-based GPS fare computation and route monitoring system for tricycle passengers in Agoo, La Union.

## Overview

GeoFare is a mobile-based application developed to promote fare transparency and enhance passenger safety for tricycle commuters in Agoo, La Union.

The system provides passengers with an independent way to estimate the appropriate tricycle fare based on GPS-calculated distance and the official fare rate provided by the Local Government Unit (LGU) of Agoo.

GeoFare also allows passengers to monitor their route during a trip, identify a tricycle through its plate number using OCR, and submit reports regarding fare-related or safety concerns. A web-based LGU dashboard allows authorized personnel to review and manage submitted reports.

## Main Features

- GPS-based fare computation
- Pickup and drop-off location capture
- Distance calculation
- Official fare rate reference
- Route monitoring during trips
- Tricycle plate number identification using OCR
- Manual plate number entry as an alternative to OCR
- Passenger trip logging
- Passenger report submission
- Web-based LGU dashboard
- Report monitoring and status management

## System Users

### Passenger

The passenger uses the mobile application to:

- Enter pickup and drop-off locations
- Calculate the estimated fare
- Monitor the route during the trip
- Capture the tricycle plate number
- Submit reports regarding fare or safety concerns

### LGU

Authorized LGU personnel use the web-based dashboard to:

- View submitted passenger reports
- Review trip and complaint details
- Monitor reported tricycle-related concerns
- Update the status of reports

## DFD

The repository contains the Data Flow Diagram (DFD) for the GeoFare system, including:

- Level 0 – Context Diagram
- Level 1 – High-Level Process
- Level 2 – Detailed Process of Trip and Fare Computation

## Structured English

The `structured-english` folder contains the Structured English documentation for the major processes of the GeoFare system.

The documented processes include:

- 1.0 Manage Trip & Fare Computation
- 1.1 Capture Pickup Location
- 1.2 Capture Drop-off Location
- 1.3 Calculate Distance & Fare
- 2.0 Manage Route Monitoring
- 3.0 Manage Plate Identification
- 4.0 Manage Reports & LGU Dashboard

## Repository Structure

```text
GeoFare/
│
├── README.md
│
├── diagrams/
│   └── DATA-FLOW-DIAGRAM (1).pdf
│
└── structured-english/
    ├── README.md
    ├── 1.1-Capture-Pickup-Location.md
    ├── 1.2-Capture-Dropoff-Location.md
    ├── 1.3-Calculate-Distance-and-Fare.md
    ├── 2.0-Manage-Route-Monitoring.md
    ├── 3.0-Manage-Plate-Identification.md
    └── 4.0-Manage-Reports-and-LGU-Dashboard.md


#Data Dictionary

The GeoFare Data Dictionary describes all database tables, fields, data types, constraints, and relationships used by the system.

### Database Tables
- PASSENGER
- TRIP
- GPS_LOG
- REPORT
- LGU_STAFF
- FARE_RATE
- PLATE_REFERENCE
- AUDIT_LOG
