Swagger UI :- http://localhost:7070/SampleGraphQlAsRestAPIWithMySqlDatabaseWithSwagger/swagger-ui/

PostMapping :-  http://localhost:7070/SampleGraphQlAsRestAPIWithMySqlDatabaseWithSwagger/getAll
RequestBody	:- 
{
    allCourses {
        id
        courseName
        rating
        price
        trainerName
        numberOfDays
    }
}

