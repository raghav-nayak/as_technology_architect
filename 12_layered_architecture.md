This is infrastructure level separation of concerns
1. **Tier 1**
	- user interface
		- views rendered in a browser
		- CLI
2. **Tier 2**
	- presentation
		- views
		- view models
		- input controllers
		- e.g. React components
	- application
		- app controllers
		- app services
		- event listeners
	- domain model
		- entities
		- collections
		- value objects
		- domain services
		- domain events
	- persistence
		- repositories
		- query objects
		- ORM
		- caching
	- infrastructure
		- framework,
		- logging
		- monitoring
3. **Tier 3**
	- data
		- database server
		- search server
		- 3rd party APIs


![[technical_architect_layered_architecture.png]]
