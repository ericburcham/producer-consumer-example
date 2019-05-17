# Producer Consumer Example
Quick producer and consumer applications for RabbitMQ using NServiceBus and .Net core.  Depends on SQL Server and RabbitMQ.



Demonstrate a broken feature.
  Broken unit test
  Broken integration test
  Error in browser
  
Fix that bug
  Make code change
  Push to git
  TeamCity --> 
    Pull sources
	Restore packages
	Compile
	Run Unit Tests
	Deploy Integration tests dependencies to containers
	  SQL
	  RabbitMQ
	Run integration tests --> Demonstrate passing
	Clean up integration test dependencies
	Deploy running application and all dependencies
	Demonstrate success in browser
