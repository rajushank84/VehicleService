# VehicleService

Basic program to manage vehicle (car/bike) service .

Will consist of two major DB tables and classes to create/update/delete:

1. Service Line Items for eg.
  - Oil change at every 6000 miles or 6 months
  - Brake pad check at every 10000 miles or 12 months
  - Steering head inspect at every 15000 miles or 24 months

2. Service Entries for eg:
  - On 2/2/2017, at 35000 miles, oil change was done
  - On 2/14/2017, at 38000 miles, brake pad check was done

Service line item will have a primary key and service entry will have a relationship to that. Service entry will have its own auto-generated primary key.

SQL scripts to be stored in the SQL folder.
Java programs to be stored in the Java folder.
