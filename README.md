# Property Management System Design Document

## Database Purpose:
- Property Management System
- Project Group: 18
- A property management system database is a crucial tool that enables property management companies to efficiently store, retrieve, manipulate and analyze their property system data. This system can be utilized across a diverse range of applications, from maintaining property details to amenity and leasing details. By adopting our database solution, companies can ensure that their data is stored and managed in a structured and organized manner, simplifying data access and analysis whenever needed.
Prospective tenants looking for rental properties often have to spend a significant amount of time visiting multiple websites and filling out numerous application forms in order to contact property management companies. With our application, all available buildings and units can be easily viewed and the rental property search process can be a hassle-free and enjoyable experience.


## Mission Objectives: 
Management Companies Side:
- To maintain data on the company.
- To maintain and search data on buildings.
- To maintain and search data on units.
- To maintain and search data on tenants.
- To maintain and search data on employees.
- To maintain and search data on leases.
- To maintain and search data on lease payments.
- To maintain and search data on amenities.
- To maintain and search data on amenity maintenance requests.
- To maintain and search data on prospective tenants.
- To maintain and search address data.
- To maintain and search data on parking fees.
- To maintain and search data on utilities fee.
- To track the status of maintenance requests.
- To calculate the vacancy rate on each building.

Tenants Side:
- To maintain and search data on unit maintenance requests.
- To update contact information of the tenant.
- To perform searches on company details.
- To perform searches on building details.
- To perform searches on unit details.
- To perform searches on amenity details.
- To perform searches on lease payments.
- To perform searches on parking fee payments.
- To perform searches on utilities fee payments.
- To perform searches on amenity details.
- To track the status of maintenance requests.
 
Prospective Tenants Side:
- To perform searches on company details.
- To perform searches on building details.
- To perform searches on unit details.
- To perform searches on amenity details.

## ERD
![image](https://github.com/SinianLiu/DAMG6210-DatabaseDesign-DataManagement-Final-Project/assets/113807640/285596db-3791-4ecb-84df-c111d7a867a8)

## Business Problems Addressed:
A database management system can help solve various problems faced by Management Companies/Landlords, as well as tenants including:-
1. Difficulty in managing multiple properties and their respective information.
Solution: This property management system can provide a centralized platform to manage information for multiple properties, making it easier for Management Companies to keep track of important information like lease agreements, rent payments, and tenant information for each property.
2. Difficulty in managing maintenance and repair requests.
Solution: With the help of this property management system, tenants can easily raise maintenance and repair requests, which can be tracked by the Management Company. This can help prioritize and manage maintenance and repairs more efficiently, reducing the time it takes to resolve issues.
 
3. Limited visibility and access to information for tenants.
Solution: The database management system can provide a platform for tenants to access information about their lease agreements, parking maintenance requests, and other important information related to their tenancy. This can improve transparency and reduce the chance of miscommunications or disputes.
4. Prospective tenants face a time-consuming process of searching for rental properties.
Solution: With a property management system, all available units can be easily viewed. This means that prospective tenants can spend less time on the search process, and can expect faster response times from property managers. With our solution, the rental property search process can be a hassle-free and enjoyable experience.


## Business Rules:
- A management company can have multiple buildings and multiple employees.
- A building can have multiple units and multiple amenities available for tenants.
- A building can have multiple employees managing it.
- A physical address is associated with each building and employee.
- Utility fees must be paid on time by the tenant.
- Parking spaces may be available to tenants for an additional fee and these must be paid on
time by the tenant.
- Each unit has an associated building and this could be leased or vacant.
- Each unit could be rented by one or many tenants and each tenant could rent one or many
units.
- A tenant can be on multiple leases and a lease can have multiple tenants.
- Lease payments must be made on time.
- Each tenant may have zero or many maintenance requests.
- Each maintenance request needs to be dealt with by one maintenance employee.
- Each maintenance request may be under two kinds of status:In Process or Completed
- A prospective tenant may express interest in multiple units.





  

