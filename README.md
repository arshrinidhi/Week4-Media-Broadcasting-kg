# Week4-Media-Broadcasting-kg
Media and Broadcasting Knowledge Graph
Checkpoint A – Topic Choice, Schema Definition, and Data Sources

Project Overview
This repository supports a term project focused on the Consumer Services sector, specifically media and broadcasting services. The goal of the project is to design a knowledge base and focused web crawler that consolidates publicly available information related to audience behavior, regulatory frameworks, service models, and broadcast technologies.

The project emphasizes open, non-proprietary data sources and adopts a knowledge graph approach to integrate heterogeneous information into a structured, queryable representation suitable for competitive intelligence and exploratory analysis.

Topic and Domain Scope
The domain includes:
1.Television broadcasters and digital media platforms
2.Content distribution services (linear TV, streaming, OTT)
3.Audience measurement and consumption trends
4.Regulatory and policy frameworks
5.Broadcast and media delivery technologies

The scope is intentionally limited to publicly accessible datasets and reports, avoiding proprietary analytics or commercial data sources.

Initial Knowledge Graph Schema
The knowledge base is designed as a graph suitable for systems such as Memgraph. Core entity types include:
1.Organization (regulators, industry bodies, broadcasters)
2.Document (reports, publications, dataset pages)
3.Dataset (downloadable statistical or analytical datasets)
4.Metric (audience, access, or service indicators)
5.Service (broadcast and media services)
6.Technology (distribution and broadcast standards)
7.Region (geographic coverage)
8.TimePeriod (year or quarter)
Relationships are explicitly typed (e.g., publishes, measures, operates_in, uses_technology) to support semantic querying and longitudinal analysis.

Data Sources
Initial data sources identified for the project include:
1.UK communications regulator research and data portals
2.International telecommunications statistical databases
3.Broadcast industry technical and research publications
These sources provide stable URLs, downloadable datasets, and longitudinal coverage suitable for automated collection and analysis.

Focused Crawler Plan
A focused web crawler is planned to collect relevant documents directly from the World Wide Web. Key design characteristics include:
1.Use of curated starter URLs
2.Relevance-driven crawling based on topic keywords
3.Text-only extraction (excluding images and multimedia)
4.Output stored as JSON Lines (JSONL) files
5.One JSON object per document, including metadata and extracted text
At this stage, the crawler and extraction pipeline are conceptual and planned, not fully implemented.
