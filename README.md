## Leap-Capstone-Project-Development-Plan
Jacob Steeg

Power Source Mapper

## Summary
# What problem does your project solve?
When planning to build a large scale campus (hospital, school, datacenter, airport), a crucial factor is to know how much electricity will be needed to support the finished structure, and where that electricity is coming from. Now more than ever, decision makers need to be cognizent of the fact that new campuses need to be built in a region with easy access to renewable energy sources.

# How does it solve the problem?
The Power Source Mapper will provide a heuristic for decision makers to visually identify the location, capacity, and the sustainability of energy sources in a given area.

# How will you achieve your MVP (minimum viable product) and what technologies, languages, and frameworks will you use?
1. collect relevent publicly accessible data from the EIA.gov database, for MVP scope only retrieving data for the state of IL (python)
2. clean data (python)
3. upload data to database (python, CosmosDB)
4. create API for database (python, flask, azure functions)
5. create frontend (react, bing maps api, azure web apps)

## Schedule

Date | Item
|---| --- |
| End of day 8th | Required P0: Finish project outline, project uploaded to GitHub, have fully cleaned Data in JSON format. |
| End of day 15th | Required P0: finish uploaded data to database, have functional API deployed  |
| End of day 22nd | Required P0: have functional front-end deployed |
| Due on 30th | MVP fully functional |

### Training Plan
[Training]
- https://www.linkedin.com/learning/building-restful-apis-with-flask?u=3322
- https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/
- https://www.pluralsight.com/courses/azure-functions-fundamentals
- https://docs.microsoft.com/en-us/learn/certifications/courses/20487
- https://www.pluralsight.com/courses/microsoft-azure-api-management-essentials
