spring-hibernate-20120924
=========================

JDBC Pain Points / ORM Requirements
-----------------------------------

Code maintenance/evolution issues:
  - entity and sql can get out of sync as code evolves
    => objects must determine DB schema!
  - one must know sql
    => should be able to just get objects from somewhere / persist objects
  - no explicit relationship between entities (one-to-one???)
    => system must know relationships and constraints

Flexibility/reuse issues:
  - code is tied to a specific SQL implementation (dialect)

General ugliness/boilerplate:
  - very repetitive code, lots of try-finally
    => forget JDBC
  - checked SQLExceptions everywhere
    => forget JDBC
  - marshalling and unmarshalling is very clumsy

Performance/correctness issues:
  - no joins
  - no transactions
  - no good way to "create table if not exists"

Videos
------

* Day 1
  * https://mrkn.s3.amazonaws.com/recordings/spring-hibernate-20120924/1.1.mov
  * https://mrkn.s3.amazonaws.com/recordings/spring-hibernate-20120924/1.2.mov
  * https://mrkn.s3.amazonaws.com/recordings/spring-hibernate-20120924/1.3.mov
  * https://mrkn.s3.amazonaws.com/recordings/spring-hibernate-20120924/1.4.mov
* Day 2
  * https://mrkn.s3.amazonaws.com/recordings/spring-hibernate-20120924/2.1.mov
  * https://mrkn.s3.amazonaws.com/recordings/spring-hibernate-20120924/2.2.mov
  * https://mrkn.s3.amazonaws.com/recordings/spring-hibernate-20120924/2.3.mov
  * https://mrkn.s3.amazonaws.com/recordings/spring-hibernate-20120924/2.4.mov