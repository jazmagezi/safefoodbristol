# Project Proposal

## Business Case

### Problem statement
Food safety in the food market is one of the key areas of focus in public health, because it affects people of every age, race, gender, and income level around the world. Failure of restaurants to ensure food safety in their respective domains leads to the contraction of foodborne illnesses by their unsuspecting customers. Foodborne illnesses are usually infectious or toxic in nature and caused by bacteria, viruses, parasites or chemical substances entering the body through contaminated food. Chemical contamination can lead to acute poisoning or long-term diseases, such as cancer. Many foodborne diseases may lead to long-lasting disability and death.

### Business benefits
The Safe Food Bristol application provides users with up-to-date information regarding the health standards of various restaurants around Bristol. This ensures that one can know whether the restaurant they desire to dine at or order from is compliant with the required food safety standards thus curbing the contraction of foodborne illnesses. The application uses data from Bristol Open Data to display information about food establishments concerning their hygiene inspection results. Users can search for restaurants, explore available ratings, and compare different establishments before deciding where to purchase food. By presenting this information in a clear and user-friendly format, Safe Food Bristol makes it easier for people to identify restaurants with high hygiene standards and avoid those with potentially concerning ratings. The application furthermore promotes public awareness of food safety, encourages restaurant owners to maintain good hygiene practices and ensures greater transparency within Bristol's food industry.

### Options Considered
#### Weighted Pugh Matrix
|  | **Weight** | **Static Website** | **Interactive Website** |
| --------- | ---------- | ----------- | ----------- |
| Data Update Functionality | 2 | S | ++ |
| Maintenance | 1 | S | - |
| Development Complexity | 2 | S | - |
| User Engagement | 1 | S | + |
| Total |  | 0 | ++ |
Therefore, the better option is to develop an interactive website.

### Expected Risks
The Safe Food Bristol application is likely to face challenges of inaccurate or incomplete data regarding hygiene ratings from Open Data Bristol which might mislead users. Additionally, data provided by Open Data Bristol might not be up to date also leading to misinformation. Other issues include unexpected changes to the format of data on Open Data Bristol that could affect the API and crush the website, security breaches from hackers opting to change ratings to boost their own restaurants, legal repercussions arising from ill representation of restaurants, failure to meet all user needs leading to bad feedback and low website traffic leading to the eventual shutdown of the website.
To mitigate these risks, the following will be undertaken. Validating information from Open Data Bristol using the Food Standards Agency, checking on whether data is updated regularly manually, monitoring the data source to be informed on an changes in format, applying HTTPS to boost website security, linking authoritative sources like the Government of UK to showcase authenticity of the data, testing with various users before deploying the app and setting up a social media page to ensure promotion of the application.  

## Project Scope
- Food Consumers
- Lecturer
- Sotfware Developer
- Government Food and Health Agencies
- Food Delivery Platforms
- Restaurant Owners
  
[Context Diagram](images/Contextdiagram.png)
