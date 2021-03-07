# what is this book about ? 

- Data intensive application explain how to handle web application when you have millions of user/transaction happening. It explains how to make back-end scalable and reliable and
How to make consistency in the applicaiton. 
Data intensive application explain in details about database, Indexing, Replication/Transaction/Partitioning/Cap Theorem, ACID/ and hell a lot of jargons we hears in software engineering.

# Chapter 1 : Reliable, Scalable, and Maintainable Applications

- Many applications today are data-intensive, as opposed to compute-intensive.
- common building blocks 
      - databases
      - Cache
      - batch processing
      - stream processing
      - indexing
  
Focus on
   - Reliability
   - Scalability
   - Maintainability


### Reliability

 - The application performs the function that the user expected.
 - It can tolerate the user making mistakes or using the software in unexpected ways.
 - Its performance is good enough for the required use case, under the expected load and data volume.
 - The system prevents any unauthorized access and abuse.

The things that can go wrong are called faults, The Netflix introduce Chaos Monkey is an example of this approach. 

A fault is usually defined as one component of the system deviating from its spec, whereas a failure is when the system as a whole stops providing the required service to the user.
