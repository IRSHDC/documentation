# Data Structure

The data structure for the DC app is central to the way people interact with the application.

## Data Defining Interaction
The DC app is essentially a viewer for records. The entire application is centered around having a great set of records, each of which have cleanly written copy and sets of related items. While the majority of the record's information will be used to populate the interface of the app, there is a component of each record that specifies to which **other** records the current one is linked. 

**Simple sets of `id` numbers, these links allow the user to navigate easily from one record to another. Collectively, are responsible for the interaction architecture of the entire app.**

## Definitions
Given that the entire user experience is based on a collection of individual records, it is important to know exactly what elements can be curated into a record.

> Please read the list of [Definitions](definitions.md)

## Processing Data (aka How Data Gets into the UI)
Once data has been created, it is equally important to know how it will be processed and represented in the application.

> Please read how data gets [Processed](processingData.md)

## Preparing Data
Creating data properly will start with the IRSHDC team. After curating content to be included in the application, the team will then generate documents that will be delivered to the development team.

> Please read how to [Prepare Data](preparingData.md)