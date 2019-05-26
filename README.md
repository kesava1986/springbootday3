# springbootday3
1.pom.xml--> JPA library
       --> Mysql configuration 
       
2.application.properties --> mysql configuration 

3.Repository --> class/interface which extends CrudRepository

4.Entity     --> Table (id,name,grade)

5.service    --> service interface, service implimentation

6.Controller --> Mofify to call the service and do CRUD operations


FLOW

url-> RestController->StudentService->StudentRepository->Entity using hibernate saves data into database table
