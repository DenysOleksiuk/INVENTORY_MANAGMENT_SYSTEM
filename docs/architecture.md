# Backend 
## com.inventory
    Main package containing other subpackages and the Spring application.
## controller 
    Is responsible only for HTTP
## service
    Is responsible only for the business logic
## repository
    Is responsible only for working with the database
## entity
    It is models for database 
## dto
    It is objects for comunication with frontend
## mapper 
    This module exists for transfering entity to dto and dto to entity
## security
    Is responsible only for working with the security 
## exceptions 
    Central proccesing exceptions module
## config
#### settings 
- DB config
- Swagger config
- Bean config 
# Frontend
## pages
- LoginPage
- DashboardPage
- ProductsPage
- SuppliersPage
## components
- Navbar
- Sidebar
- ProductTable
- Modal
- Form
## api
- axiosClient
- productApi
- authApi
  architecture
