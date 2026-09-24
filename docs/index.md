## 0. Introduction

Data analytics is the process of examining data to answer questions, generate insights, support decision-making, and measure outcomes. It involves understanding business needs, acquiring and preparing data, applying analytical techniques, and communicating findings in a way that drives action.

This workflow is intended for projects where data is used to explore, explain, predict, monitor, or support decisions. In the first section you will select the analytics "route" that best reflects the work, each section will then have guidance specific to your selected route.

## 1. Project framing

> Establish what the client needs, why analytics is an appropriate response, and which analytics route best fits the problem.

### Key activities
- Confirm the business question, decision context and users.
- Agree the expected level of reuse, longevity and assurance.
- Identify data sensitivity, client constraints, hosting needs and security considerations.
- Select analytics route
- Define scope and deliverables


=== "Exploratory Analysis"

    **Purpose**

    Answer a question or investigate a problem where the outcome is not yet known.

    **Use when**

    - One-off investigation
    - Internal evidence gathering
    - Early-stage discovery

    **The client asks**

    > What is happening and why?

    **Examples**

    - Why have customer complaints increased?
    - What factors contribute to network incidents?
    - Which assets are most likely to fail?

    **Expected controls**

    - Simple repository
    - Documented notebooks/scripts
    - Peer review

    **Typical outputs**

    - Insights report
    - Recommendations
    - Root cause analysis
    - Opportunity assessment


=== "Repeatable Analysis"

    **Purpose**

    Create a repeatable analytical process that can be rerun as new data becomes available.

    **Use when**

    - Analysis needs to be rerun or refreshed

    **The client asks**

    > How is performance changing over time?

    **Examples**

    - Benefits tracking
    - Quarterly customer segmentation

    **Expected controls**

    - Structured repository
    - Configuration management
    - Tests for key transformations
    - Reproducible environment

    **Typical outputs**

    - Analytical workflow
    - Automated reports
    - KPI calculations
    - Scheduled analysis

### Exit criteria
- The client problem or opportunity is clearly defined.
- The intended users and decision-makers are identified.
- The primary analytics route has been selected.
- The key analytical questions are documented.
- Expected outputs and deliverables are agreed.
- Success measures and acceptance criteria are defined.
- Scope, assumptions, constraints and exclusions are understood.
- Initial data, ethical, privacy and governance risks have been identified.


## 2. Setup
> Establish the people, tools, environments and governance needed to deliver the project.

### Key activities
- Establish ways of working
- Setup technical delivery structure
- Define governance and assurance
- Review reusable patterns and assets

### Inputs
Link to environment setup
Ways of working guidance: we recommend an agile approach, e.g. : https://basecamp.com/shapeup 

### Exit criteria
- Repository created
- Environments available
- Access obtained
- Delivery approach agreed
- Governance approach defined
