# Budget
Don't edit this - the RPPR generator populates this section

# Research Design

CTSA hubs produce many valuable datasets which can be shared across the broader research community. A significant gap exists between the data providers and the data discovery portals where researchers look for relevant datasets (including the generic Google Dataset search and many biomedical specific data portals). Data providers typically lack sufficient guides to expose their dataset metadata to these data portals.

On the other hand, the data-portal developers who need to define their own metadata schemas often lack of effective ways to navigate the existing metadata schemas and extend them to fit their own need. This is significant to the end users as well, because the initial schema design decisions impact the interoperability of the entire datasets available from a data-portal.

In this project, we are building interactive widgets and development tools to support both data-providers and developers, promoting data-sharing best-practices among the CTSA community.


# Methodology

In recent years, [Schema.org](https://schema.org) has been widely adopted in the consumer-facing web-publication and software engineering fields to enhance the distributed metadata harmonization. All major web search engines, like Google and Bing, have adopted this technology to provide users more accurate and enriched search results. The adoption of the schema.org technology in the biomedical field has been emerging more recently, such as "[BioSchemas](https://bioschemas.org)" effort.

This project will build a collection of tools to bridge the schema.org technology and the specific biomedical use-cases coming from CTSA's real-world applications. Develop and bring the latest data-sharing best-practices to the CTSA community. The set of tools are grouped into these three components:


**Metadata widgets**


**Schema Hub**


**Data-portal Integration**


# Expected Outcomes

- **Metadata widgets** to help data providers to build and submit dataset metadata
    - Dataset hosting selector with example hosting options.
    - Dataset licence selector with CreativeCommons license supported.
    - Dataset metadata authoring tool supports multiple data portals.

- **Schema Hub** to help developers to build metadata schemas on top of existing ones
    - Implementing a schema.org based schema indexer.
    - Implementation a user schema registering interface.
    - Implement a schema search interface to allow users to extend existing ones.

- **Data-portal Integration**
    - Harvest distributed dataset metadata and trigger the metadata-indexing at specific data-portals like [MenRva](https://github.com/data2health/menRva).

# Deliverables

A collaborative guidebook, an interactive web portal, and an metadata-authoring web portal

# Timeline (monthly)
- 7/1/19 Identify and define initial set of metadata schemas to be supported
- 8/1/19 **Metadata widgets** Initial metadata-authoring form and metadata-hosting ready
- 8/1/19 **Schema Hub** Schema.org based schema indexer backend ready
- 9/1/19 **Metadata widgets** Support biomedical-specific metadata schemas (go beyond basic metadata fields from Google dataset search)
- 9/1/19 **Schema Hub** User interface for schema-builder by extending existing schemas ready
- 9/1/19 **Data-portal integration** Focus on building integration with [MenRva data portal](https://github.com/data2health/menRva)
- 10/1/19 Reach out to CTSA community to expand the support for additional dataset discovery use-cases.
- 11/1/19 Engage data portal community to share metadata schemas (CTSA, DASH, NIAID etc.)
- 12/1/19 Explore the connections with other CD2H projects (e.g. expanding the platform to support other resource types)


# Potential Pitfalls and Alternative Strategies

* Incentives for motivating data-providers

    As a relatively new technology in the biomedical field, motivating the early adopters can always be a challenging task. We will take agile development strategy, work closely with the specific datasets or research projects and identify the steps during the data-sharing process which can be generalizable to the other datasets or projects. That way we can incrementally accumulate the practical incentives for the researchers who are working with datasets directly.


* Breadth of the covered use-cases

    As we target to build user-friendly web widgets and development tools to simplify the data-sharing process, the initial covered use-cases can be limited. At the first six-month period of year-3, we will focus on demonstrating the utility of the application by using selected use-cases. They will also serve as the incentives to attract more use-cases at the later stage of the project. Using our biweekly "Metadata" community meeting as the channel, we will reach out to our potential users and increase the breadth of the covered use-cases.

