## System design template for 'X'
1. What is X
2. Requirements and Goals of the System
    * Functional Requirement
    * Non-Functional Requirement (Available, latency, consistency, reliable(not lost))
    * Extended Requirement
3. Capacity Estimation and Constraints
    * Traffic estimates
    * Storage estimates
    * Bandwidth estimates
    * Memory estimates (80 - 20 rules that is 20% data generates 80% traffic daily)
4. System APIs
5. Database Design
6. High level Design
7. Component Design
    * Application Layer
        * How to handle a write-request
        * How to handle a read-request
    * Database Layer
        * Metadata storage/database
        * Object storage
    > Finish Detail design after Database layer
8. Data Partitioning and Replication
9. Cache
10. Load Balancer
11. Purgin or DB Cleanup
12. Security and permission

## System design category wise:
* Designing a storage/sharing service: Dropbox, Youtube, Instagram, etc.
* Designing a service that deals with geographical data: Uber, Yelp, Lyft, etc.
* Designing a social media service: Facebook, Twitter, Instagram, Snapchat, etc.
* Designing a communication service: Messenger, High traffic web server, etc.
* Designing a search related service: Search engine, Web crawler, etc.
* Designing location sharing service: Uber, Google map, Zomato

## Resources
1. [Gaurab System design youtube](https://www.youtube.com/watch?v=xpDnVSmNFX0&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&ab_channel=GauravSen)
2. [Free code camp](https://www.freecodecamp.org/news/how-to-system-design-dda63ed27e26/)
3. [Wide Column database](https://stackoverflow.com/questions/62010368/what-exactly-is-a-wide-column-store)
4. [System Design Primer](https://github.com/donnemartin/system-design-primer)
5. [System Design Medium](https://systemdesign.medium.com/)
6. [System Design Interview - Youtube Channel](https://www.youtube.com/c/SystemDesignInterview/videos)
7. [System Design  Course Github](https://github.com/karanpratapsingh/system-design)
8. [System Design Interview Github](https://github.com/checkcheckzz/system-design-interview)
9. [Crack the System Design Interview](https://tianpan.co/notes/2016-02-13-crack-the-system-design-interview)
10. [System Design Interview Questions – Concepts You Should Know](https://www.freecodecamp.org/news/systems-design-for-interviews/)
11. [Leetcode System Design](https://leetcode.com/discuss/interview-question/system-design?currentPage=1&orderBy=hot&query=)


