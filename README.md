**Graduation project GeekBrains**
*Author: Yuzhakov Mikhail*

*Content*
* Technical task
* Application structure
* Elements description
* Results

__Technical task__

The purpose of this work is to develop a repository for soil-climatic parameters.
Language: Java.
Requirements:
- The data must be stored in a relational database.
- TCP/IP (TLS) server must be implemented to interact with endpoint devices.
- Simple web interface (using HTTP) must be implemented for user interaction with database.
- Discretionary access sharing must be implemented by using authorization system.

__Application structure__

The application must be implemented on the Linux operating system (or not?).
1. Data base.
    - Data base is builded by using postresql.
    - Need to realize requests processing.

2. TCP/TLS Server.
    - ServerSocket API using.

3. HTTP Server.
    - HTTPServer using.

4. Simple web-interface.
    - First tab - authorization page;
    - Second tab - data view page;
    - Third tab - log.

__Results__

The result must be a web interface prototype for storing any data set, processing database queries and a simple visual.
