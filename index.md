---
layout: default
title: Workflow
---

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

=== "Model Development"

    **Purpose**

    Develop statistical, forecasting, optimisation, or machine learning models that support decision-making.

    **Use when**

    - Statistical modelling
    - Simulation
    - Optimisation
    - Machine learning

    **The client asks**

    > What is likely to happen?

    **Examples**

    - Demand forecasting
    - Incident prediction
    - Customer propensity modelling
    - Asset deterioration modelling

    **Expected controls**

    - Model specification
    - Validation
    - Assumptions log
    - Review record

    **Typical outputs**

    - Predictive models
    - Forecasts
    - Risk models
    - Classification models

=== "Dashboard & Reporting"

    **Purpose**

    Enable ongoing monitoring of performance through self-service reporting and visualisation.

    **Use when**

    - Power BI, Dash, Tableau, or similar reporting solutions

    **The client asks**

    > How can we make this visible to others?

    **Examples**

    - Service performance dashboard
    - Executive reporting pack
    - Operational management dashboard

    **Expected controls**

    - Data model
    - Visual QA
    - UAT
    - Refresh and support plan

    **Typical outputs**

    - Power BI dashboards
    - Operational reports
    - Executive scorecards
    - KPI monitoring solutions

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

## 3. Data discovery

> Identify, access, understand and assess the data needed to answer the analytical questions.

### Activities
- Identify data sources
- Obtain access
- Profile data
- Assess quality
- Assess ability to answer analytical question
- Document limitations

### Inputs
?

### Exit criteria
- Data sources identified
- Data quality understood
- Risks and gaps documented
- Data suitability confirmed

## 4. Design
> Design how the project will transform data into evidence, insight, predictions, monitoring information or recommendations.

### Activities
- Design analytical approach
- Define metrics and calculations
- Design outputs
- Define validation approach

### Inputs
?

### Exit criteria
- Analytical design agreed
- Validation approach agreed
- Key assumptions documented

## 5. Iterative build
> Develop the analysis or analytical product in manageable increments, adapting the solution as understanding improves.

### Activities
- Build solution
- Refine approach
- Document decisions
- Manage backlog and change

### Inputs

- Code collaboration
- UI/UX guidance

### Exit criteria

- Solution implemented
- Documentation maintained
- User feedback incorporated
- Ready for testing

## 6. Testing, validation and assurance
> Confirm the solution is correct, reliable, understandable and suitable for its intended use.

### Activities
- Perform technical testing
- Validate outputs
- Conduct user acceptance testing
- Update backlog

### Inputs
- ?

### Exit criteria
- Testing completed
- Issues accepted or added to backlog
- Validation evidence recorded
- Approved for release

## 7. Delivery
> Prepare, approve and release the analytical output/increment through an appropriate channel so that intended users can access, understand and use it.

### Activities
- Deploy or publish solution
- Configure access
- Complete release activities
- Communicate release
- Verify production operation

### Inputs
- ?

### Exit criteria
- Solution published
- Users have access
- Documentation available
- Release accepted

### Iterate
> Iterate as needed. New insights, user feedback, or changing requirements may require a return to Data Discovery (3), Design (4), or Iterative Build (5) before proceeding.

## 8. Handover
> Transfer the knowledge, responsibilities and assets needed for the client or receiving team to operate, maintain and improve the analytical solution.

### Activities
- Deploy or publish solution
- Configure access
- Complete release activities
- Communicate release
- Verify production operation

### Inputs
- ?

### Exit criteria
- Ownership assigned
- Knowledge transferred
- Support model agreed
- Project closed

### Additional
- Patterns written up and added to GHD wiki
- 
