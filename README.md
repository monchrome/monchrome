## Hi there 👋

<!--
**monchrome/monchrome** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile. -->

I am Monika Borgaonkar

- Developer, Security & Performance Pioneer, Lead Architect, Tech Lead, Technical Manager, Speaker at TechReady and Build conferences, On panel expert at Dreamforce.
- Mastered the art of becoming the "GoTo" person for all features/services/products I have owned.
- Pioneered the efforts for starting women's cricket team in Seattle, WA.
- Love light hikes and playing board games.
- Love reading tech blogs.

**AI Agents/MCP/Projects Implemented -**
- BillTally&Reconcile - Developed a Claude based AI-driven agent to perform automated billing tallying, reducing manual audit overhead and improving data accuracy. A custom Claude-based agent is a specialized, reusable AI assistant powered by Anthropic's Claude models. Tech Stack - Python, LangChain, Claude Opus 4.8, Custom tools calling CBE APIs.
- CVRAgent - Built a custom Python based agent integrated with an in-house git hub MCP server to autonomously identify and patch CVE-based vulnerabilities across codebase repositories. Tech Stack - Python, LangChain, inhouse GitHub MCP Server.
- ReflectiveAgent - Built a  Kotlin-> Java code migration agent using reflective agentic pattern. Tech Stack - Java, Claude Sonnet (for generation) and Claude Opus 4.8 (for reflection). Models can be preset via configuration.
- SystemPromptMigrator - Built a System prompt migrator service to do semantic migration of system prompts from a source LLM to a target LLM.  Syntax, formatting idioms, verbosity, system-instruction placement, JSON-format enforcement, and chain-of-thought style all vary drastically between model families — so the rewrite is performed by the target
model itself. Tech Stack - Python, Fast API, Pydantic.
- RAGForTaxChatBots (in progress) - Neo4J Graph based RAG and a chatbot to answer questions related to CA personal taxation. Tech Stack - Neo4J, ChromaDB (to lower cost) /Voyage AI , Ollama nomic-embed-text, Claude Opus 4.8., LangChain, RecursiveCharacterTextSplitter
-  sfdcmcpsrv - A Java-Spring Boot custom MCP server that exposes Salesforce REST API operations to AI clients. Tech Stack - Java 25, Spring Boot 4.1.0, Spring AI 2.0.0. Needs a Salesforce Connected App/equivalent.

**Major Publications -** 
- https://www.microsoft.com/en-us/download/details.aspx?id=12108 ⇒ Contributed content to this white paper explaining authN, authZ and overall security model implemented in Dynamics CRM.
- https://www.microsoft.com/en-us/download/details.aspx?id=12774  ⇒ Contributed content for this white paper w.r.t firewall connectivity for onpremise setups of Dynamics CRM.
- https://www.microsoft.com/en-us/download/details.aspx?id=2684  ⇒ Contributed content for this white paper, explaining how Active Directory Federation Service(ADFS) is to be used for Internet facing deployment of Dynamics CRM.
- https://medium.com/@davinciwords/http-connection-pooling-handling-post-redirects-as-post-c908266768b2 ⇒ Published this article based on some observations w.r.t a production incident observed in Salesforce.

**Major Creations and Significant Contributions -**
- Started the first single person security team in Microsoft Dynamics CRM and grew the team to 10.
- Based on my handling of Security team was asked to lead Performance for entire Microsoft Dynamics CRM.
- Established cross product collaboration practices for security and performance across Microsoft Dynamics CRM, Sharepoint and Microsoft Office security teams.
- Creator of SQLInjector, XSSSentinelInjector, SoapAPIFuzzer infrastructure that would help unveil security issues in daily software builds.
- Contributed both in terms of design, secure config, setup on many aspects to make  Dynamics CRM online a secure online service from day 1.
- Contributed majorly towards fulfilling software design requirements for ISO-9001, FedRAMP, GDPR compliance related security and privacy requirements.
- Pioneered Base and Extension table separation to ease form load times for Dynamics CRM. 
- Contributed majorly towards integrating High Availability Disaster Recovery(HADR) feature for Dynamics CRM data center failover procedures 
 in a manner that they meet 45 mins SLA for failover of 700 tenant databases from one DC to another.
- Completely redesigned content security for Salesforce Communities Platform to prevent Remote code execution, Elevation of Privilege Threats.
- Primary Developer/Tech Lead for Platformization of Opportunity Scoring for Sales Cloud Einstein at Salesforce.
- Designed and Developed Global Model Contributions for AI for Everyone program.
- Developer of https://developer.salesforce.com/docs/atlas.en-us.object_reference.meta/object_reference/sforce_api_objects_salesaiscorecycle.htm)
- Developer of https://developer.salesforce.com/docs/atlas.en-us.object_reference.meta/object_reference/sforce_api_objects_salesaiscoremodelfactor.htm
- Implemented Cloud to Cloud Authentication backend modules for Authenticating requests between Salesforce and AWS services and between Core and Einstein cloud of Salesforce.

**Major Architectural Contributions -**
- Delivered architectural design and implementation of fintech & issuer Billing service at Visa Inc.
- Delivered architectural design and implementation of fintech authorizations for allowing usage of Visa APIs.
- Devised the architecture of CRVAgent (a tool that will fix CVE's for containerized applications.)
- Implemented architectural design, implementation of sandboxing content uploads before they are deemed secure for further distribution.
- Designed the overall architecture and implementation of authZ model for Salesforce Opportunity Scoring. 
- Designed the overall architecture and implementation of authZ model for global model trainings and allow cross tenant data collection into global model usage.
- Designed solution for allowing all microservices to use AWS STS token and gain access to only requested resources on AWS S3.
- Designed solution for tenant org migrations from one AWS region to another.
- Devised the entire architecture of automated Fuzzers for CRM Soap APIs.

