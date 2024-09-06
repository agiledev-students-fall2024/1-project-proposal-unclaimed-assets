## Project Proposal

### Project Title

**Unclaimed Property Aggregator**

### What and Why?

I propose one group builds a software system that aggregates unclaimed property data from all U.S. states into a single platform. Each state currently has its own unclaimed property website (for example -- [NY](https://www.osc.ny.gov/unclaimed-funds) and [CA](https://www.sco.ca.gov/search_upd.html)), but these are not widely known or used by the general public. The goal of this system is to solve the problem of unclaimed property going unnoticed or unclaimed due to the fragmented nature of current state-run systems.

By aggregating this data into one app and notifying users when new unclaimed property is found, we make it significantly easier for people to discover and claim property that rightfully belongs to them. This could range from forgotten bank accounts, stocks, uncashed checks, insurance benefits, wages, and even safe deposit box contents. By providing an all-in-one solution that alerts users about potential new claims, we increase the likelihood of them reclaiming their lost assets.

### For Whom?

The target audience for this app includes anyone who may have unclaimed property in the U.S. Essentially, it is for any individual who wants to be alerted if they have unclaimed property they are owed. This includes mass consumers, families, and businesses, as well as specific groups like college students, retirees, and frequent movers who might be more likely to have unclaimed property in multiple states.

By having real users across a broad demographic, we can refine the design to make it intuitive and accessible, ensuring a wide reach and impact.

### How?

From an end-user's perspective, the system will provide the following functionalities:

1. **User Registration and Profile Management**: Users will sign up and create a profile with their relevant details (name, previous addresses, etc.).
2. **Search and Aggregation**: The app will automatically search unclaimed property databases in all U.S. states using APIs where available, or through web scraping techniques if APIs are not provided.
3. **Alert System**: The app will notify users when new unclaimed properties are found that match their profile details.
4. **Claim Assistance**: It will provide detailed instructions or a direct link to the appropriate state’s website to facilitate the claiming process.
5. **Dashboard and Tracking**: A user dashboard will display any properties found and track the status of their claims.

### Scope

The proposed project is challenging yet manageable for a group of 4 to 6 programmers to undertake in one semester. It involves:

- **Research and Data Structuring**: Understanding the best ways to structure data coming from various state databases or scraped from their websites.
- **API Integration and Web Scraping**: Developing modules for both API integration (where available) and web scraping for states that do not provide APIs.
- **Backend and Frontend Development**: Building a user-friendly frontend and a robust backend to handle data aggregation, storage, and notifications.
- **Performance Optimization**: Implementing cost-effective techniques for periodic data updates and notification delivery.

