# springbootday3
pom.xml--> JPA library
       --> Mysql configuration
application.properties --> mysql configuration
Repository --> class/interface which extends CrudRepository
Entity     --> Table (id,name,grade)
service    --> service interface, service implimentation
Controller --> Mofify to call the service and do CRUD operations


url-> RestController->StudentService->StudentRepository->Entity using hibernate saves data into database table
