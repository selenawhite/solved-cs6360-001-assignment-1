Download Link: https://assignmentchef.com/product/solved-cs6360-001-assignment-1
<br>
<strong>Database Design </strong>




<strong> </strong>

<ol>

 <li>Following is the data requirements for an art museum:</li>

</ol>




<ul>

 <li>The museum has a collection of ART_OBJECTS . Each art object has a unique IDNo, and Artist, if known, a Year (when created, if known) a Title and a Description.  The art objects are categorized in several ways, as discussed below.</li>

 <li>ART_OBJECTS are categorized based on types. There are three main types, Painting, Sculpture and  Statue, plus an ‘Other’ category for those that don’t fit into one of the main types.</li>

 <li>A PAINTING has a PaintType (oil, watercolor, etc) a material on which it is CrawnOn (paper, canvas, wood) and Style (modern, abstract etc)</li>

 <li>A SCULPTURE or a STATUE has a Material from which it was created (wood, stone, etc) Height, Weight and Style.</li>

 <li>An art object in the OTHER category has a Type(print, photo, etc) and Style.</li>

 <li>ART_OBJECTS are also categorized as PERMANENT_COLLECTION, which are owned by the museum (DateAcquired, whether it is OnDisplay or Stored and Cost) or BORROWED, which has information on the Collection (where it was borrowed from), DateBorrowed, and DateReturned.</li>

 <li>ART_OBJECTS also have information describing their country-culture using information on country/culture of Origin (Italian, Egyptian, American, Indian etc) and Period(Renaissance, Modern, Ancient)</li>

 <li>The museum keeps track of ARTISTS’s information, if known: Name, DateBorn, DateDied, CountryOfOrigin, Period, MainStyle and Description. The name is assumed unique.</li>

 <li>Different EXHIBITIONS occur, each having a Name, StartDate and EndDate. EXHIBITIONS are related to all the art objects that were on display during the exhibition.</li>

 <li>Information is kept on other COLLECTIONS with which the museum interacts, including Name (unique), Type (museum, personnel etc), Description, Address, Phone and ContactPerson.</li>

</ul>




Draw an EER diagram for this application.  Discuss any assumptions you make.




<strong> </strong>

<strong> </strong>

<strong> </strong>

<ol start="2">

 <li>Consider the following set of requirements for an investment company database. Draw an ER or EER diagram that captures the details specified below. State your assumptions if any.</li>

</ol>

<ul>

 <li>The investment company has several branches. Each branch has a BranchId (which is unique), address, phone and a manager.</li>

 <li>Each branch has a number of customer accounts, each of which has a unique account number, owner and an employee who acts as portfolio advisor. An account has only one owner. An employee may be the advisor for many accounts.</li>

 <li>Each person (customer or employee) has SSN, name, address, and phone. Every customer has exactly one account. Each person has a unique SSN. Due to conflict of interest, employees are prohibited from having an account with the investment company.</li>

 <li>Each account has within it a number of stock holdings: stock symbol, name, and quantity. The quantity is further broken into lots that were purchased together. Each lot has quantity, purchase price per unit share, and date of purchase. For example, an account may have 500 shares of MSFT (Microsoft Corp), which were purchased in 2 lots: 200 shares at $25.75/share on 9/9/11, and 300 shares at $26.20/share on 10/4/11.</li>

</ul>










<strong> </strong>

<ol start="3">

 <li>Map the ER/EER diagram in your answer to previous question into the relational model.</li>

</ol>




<ol start="4">

 <li>Consider the ER diagram in following figure. Map the given conceptual schema to relational database schema.</li>

</ol>

<strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong> </strong><strong>5.</strong> Consider the EER diagram in below figure for a car dealer. Map the EER schema into a set of relations. For the VEHICLE to CAR/TRUCK/SUV specialization, consider the four options (8A, 8B, 8C, 8D) and show the relational schema design for all options.




<strong>Each question is 20 points. </strong>

<strong> </strong>

It is optional to use an ER diagram tool for drawing ER/EER diagrams.


