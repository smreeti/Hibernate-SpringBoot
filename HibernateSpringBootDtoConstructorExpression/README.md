**[DTOs via Constructor Expression and JPQL](https://github.com/AnghelLeonard/Hibernate-SpringBoot/tree/master/HibernateSpringBootDtoConstructorExpression)**

**Description:** Fetching more data than needed is prone to performance penalities. Using DTOs allows us to extract only the needed data. In this application we rely on Constructor Expression and JPQL.

**Key points:**\
     - write a proper constructor in the DTO class\
     - use a query as `select new com.bookstore.dto.AuthorDto(a.name, a.age) from Author a`\
     - for using Spring Data Projections check this [recipe](https://github.com/AnghelLeonard/Hibernate-SpringBoot/tree/master/HibernateSpringBootDtoViaProjections) 

**See also:**\
[Dto Via Constructor And Spring Data Query Builder Mechanism](https://github.com/AnghelLeonard/Hibernate-SpringBoot/tree/master/HibernateSpringBootDtoConstructor)

<a href="https://leanpub.com/java-persistence-performance-illustrated-guide"><p align="center"><img src="https://github.com/AnghelLeonard/Hibernate-SpringBoot/blob/master/Java%20Persistence%20Performance%20Illustrated%20Guide.jpg" height="410" width="350"/></p></a>
