- 👋 Hi, I’m @kaeaddaar. My name is Clifford MacKay
- I build software integrations and tools to help automate sending POS & ERP data to E-Commerce web sites and more
- I like to program using C# and that includes client side in the browser. 
- I wish I had time to collaborate more, but am always looking for the right people to work with and projects to work on
- I want to choose projects that help me build up technology to help make it easier to connect software. You could call it ETL, but the approach is different.
 - My approach is to build the 3 pieces of the Extract Transform Load (ETL) puzzle as separate projects where I keep building up the tech to make the next project easier. 
 - Extract (E): My main project that kicked this off was a project to gain direct access to ODBC data for a POS System. The helped solve problems with complex transformation logic, business rules, caching methods, and more. 
 - Transform (T): The first use of this project was to create a windows service that transformed the results of the project above into a common data format between the POS system and a web store. Then we detect changed records and send just changed records across the wire to the other program using their tool to pull and update records. This became the place to write our report, build our logs, automate all those little ideas we had to make life easier, and more. 
 - Load (L): The tools for loading data to the web store have yet to be broken out into their own project. When the web store finishes the next version of their API I plan to move this functionality into its own project.
 
 My idea is to bring technology together that can help us build a platform where software talks to software. Imaging having a screen with a big E, T, and L on it that you drag a software component onto. We could drag my main project onto the E, the next project I built onto the T, and the new Web Store integration onto the L. We can install any necessary components and then the customer starts using their integration. They decide they want some reports so they drag the canned reports they want to a spot next to the T in the Transform. That's the future of the product, but for now we build the simple building blocks moving step by step towards that utopian ideal.
 
 If I focus on building components that Talk to Software (The E and L in ETL). Then even if an integration doesn't exist you could drag and drop fields from the schemas to build a common schema to auto create the (T) portion of the puzzle. Then write custom code as necessary for any additional logic or connectors. Currently I talk to System Five, Dakis Web Stores, Shopify, Beverage Network price sheets, and am always dreaming up the next target on the list. 

