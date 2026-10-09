## Introduction

Data analytics is the process of examining data to answer questions, generate insights, support decision-making, and measure outcomes. It involves understanding business needs, acquiring and preparing data, applying analytical techniques, and communicating findings in a way that drives action.

This workflow is intended for projects where data is used to explore, explain, predict, monitor, or support decisions. In the first section you will select the analytics "route" that best reflects the work, each section will then have guidance specific to your selected route.

---

## 1. Project framing

> Establish what the client needs, why analytics is an appropriate response, and which analytics route best fits the problem.

### Key activities
- Confirm the business question, decision context and users.
- Agree the expected level of reuse, longevity and assurance.
- Identify data sensitivity, client constraints, hosting needs and security considerations.
- Select analytics route.
- Define scope and deliverables.

=== "Exploratory Analysis"

    **Purpose**

    Answer a question or investigate a problem where the outcome is not yet known.

    **The client asks**

    > What is happening and why?

    **Examples**

    - Why have customer complaints increased?
    - What factors contribute to network incidents?
    - Which assets are most likely to fail?

    **Typical outputs**

    - Insights report
    - Recommendations
    - Root cause analysis
    - Opportunity assessment


=== "Repeatable Analysis"

    **Purpose**

    Create a repeatable analytical process that can be rerun as new data becomes available.

    **The client asks**

    > How is performance changing over time?

    **Examples**

    - Benefits tracking
    - Quarterly customer segmentation

    **Typical outputs**

    - Analytical workflow
    - Automated reports
    - KPI calculations
    - Scheduled analysis


=== "Model Development"

    **Purpose**

    Develop statistical, forecasting, optimisation, or machine learning models that support decision-making.

    **The client asks**

    > What is likely to happen?

    **Examples**

    - Demand forecasting
    - Incident prediction
    - Customer propensity modelling
    - Asset deterioration modelling

    **Typical outputs**

    - Predictive models
    - Forecasts
    - Risk models
    - Classification models


=== "Dashboard & Reporting"

    **Purpose**

    Enable ongoing monitoring of performance through self-service reporting and visualisation.

    **The client asks**

    > How do I monitor and communicate this?

    **Examples**

    > Service performance dashboard
    > Executive reporting pack
    > Operational management dashboard

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

---

## 2. Setup
> Establish the people, tools, environments and governance needed to deliver the project.

### Key activities
- Establish ways of working
- Setup technical delivery structure
- Define governance and assurance
- Review reusable patterns and assets

### Guidance
- Setup working environments as per wiki guidance (_Link to environment setup_)
- An agile approach to project delivery is recommended, for example: [Shape Up] (https://basecamp.com/shapeup)
- Guidance for repository setup: https://cookiecutter-data-science.drivendata.org/ 

=== "Exploratory Analysis"
    Additional activities:
    - Agree key questions and hypotheses to investigate
    - Identify potentially relevant datasets and SMEs
    - Set expectations that findings may change project direction
    - Establish workspace for rapid analysis and experimentation
    - Prepare for the following expected controls:
       - Simple repository
       - Documented notebooks/scripts
       - Peer review
 
=== "Repeatable Analysis"
    Additional activities:
    - Define frequency of execution and operational ownership
    - Identify opportunities for automation from the outset
    - Agree reproducibility and documentation standards
    - Establish source control and deployment approach
    - Prepare for the following expected controls:
       - Structured repository
       - Configuration management
       - Tests for key transformations
       - Reproducible environment
 
=== "Model Development"
    Additional activities:
    - Confirm prediction/classification objective and success metrics
    - Identify required modelling tools and compute resources
    - Define model governance requirements
    - Agree validation and approval approach
    - Prepare for the following expected controls:
             - Model specification
             - Validation
             - Assumptions log
             - Review record
 
=== "Dashboard & Reporting"
    Additional activities:
    - Confirm audience groups and decision-makers
    - Identify reporting platform and hosting environment
    - Define security and access requirements
    - Agree publication and refresh responsibilities
    - Prepare for the following expected controls:
       - Data model
       - Visual QA
       - UAT
       - Refresh and support plan

### Exit criteria
- Repository created
- Environments available
- Access obtained
- Delivery approach agreed
- Governance approach defined
- Team is mobilised

---

## 3. Data discovery

> Identify, access, understand and assess the data needed to answer the analytical questions.

### Activities
- Identify data sources
- Obtain access
- Profile data
- Assess quality
- Assess ability to answer analytical question
- Document limitations

### Guidance
- Methodology for data discovery: https://www.ibm.com/docs/it/SS3RA7_18.3.0/pdf/ModelerCRISPDM.pdf (this is partially tied to a software but the advice is mostly generic)

=== "Exploratory Analysis"
    Additional activities:
    - Assess breadth of available data sources
    - Identify gaps that may limit investigation
    - Explore unusual variables and potential indicators
    - Prioritise fast access to data over complete integration
 
=== "Repeatable Analysis"
    Additional activities:
    - Assess long-term availability and stability of data sources
    - Evaluate data refresh mechanisms
    - Identify recurring quality issues
    - Document source-to-output lineage requirements
 
=== "Model Development"
    Additional activities:
    - Assess target variable availability and quality
    - Identify features that may influence outcomes
    - Examine historical coverage and volume
    - Assess class imbalance and bias risks
 
=== "Dashboard & Reporting"
    Additional activities:
    - Identify KPIs, dimensions and reporting hierarchies
    - Assess data readiness for visualisation
    - Understand reporting granularity requirements
    - Identify trusted data sources for business reporting

### Exit criteria
- Data sources identified
- Data quality understood
- Risks and gaps documented
- Data suitability confirmed

---

## 4. Design
> Design how the project will transform data into evidence, insight, predictions, monitoring information or recommendations.

### Activities
- Design analytical approach
- Define metrics and calculations
- Design outputs
- Define validation approach

### Guidance
- OKRs as a method to improve goal setting: https://www.whatmatters.com/get-examples

=== "Exploratory Analysis"
    - X
 
=== "Repeatable Analysis"
    - Y
 
=== "Model Development"
    - Z
 
=== "Dashboard & Reporting"
    - A

### Exit criteria
- Analytical design agreed
- Validation approach agreed
- Key assumptions documented

### Iterate
> Iterate as needed. If the data collected is not sufficient to support the metrics or outputs identified, it may require a return to Data Discovery (3) before proceeding.

---

## 5. Build
> Develop the analysis or analytical product in manageable increments, adapting the solution as understanding improves.

### Activities
- Build solution
- Refine approach
- Document decisions
- Manage backlog and change

### Guidance
- Code collaboration
- UI/UX guidance and examples: https://lawsofux.com/, https://m3.material.io/, https://design-system.service.gov.uk/
- Data visualisation guidance: https://royal-statistical-society.github.io/datavisguide/, https://service-manual.ons.gov.uk/data-visualisation

=== "Exploratory Analysis"
    - X
 
=== "Repeatable Analysis"
    - Y
 
=== "Model Development"
    - Z
 
=== "Dashboard & Reporting"
    - Dashboard design guidance: https://www.datacamp.com/tutorial/dashboard-design-tutorial

### Exit criteria

- Solution implemented
- Documentation maintained
- User feedback incorporated
- Ready for testing

---

## 6. Testing, validation and assurance
> Confirm the solution is correct, reliable, understandable and suitable for its intended use.

### Activities
- Perform technical testing
- Validate outputs
- Conduct user acceptance testing
- Update backlog

### Guidance
- ?

=== "Exploratory Analysis"
    - X
 
=== "Repeatable Analysis"
    - Y
 
=== "Model Development"
    - Z
 
=== "Dashboard & Reporting"
    - A

### Exit criteria
- Testing completed
- Issues accepted or added to backlog
- Validation evidence recorded
- Approved for release

---

## 7. Delivery
> Prepare, approve and release the analytical output/increment through an appropriate channel so that intended users can access, understand and use it.

### Activities
- Deploy or publish solution
- Configure access
- Complete release activities
- Communicate release
- Verify production operation

### Guidance
- To help ensure that project outputs tell an effective story: https://www.effectivedatastorytelling.com/

=== "Exploratory Analysis"
    - X
 
=== "Repeatable Analysis"
    - Y
 
=== "Model Development"
    - Z
 
=== "Dashboard & Reporting"
    - A

### Exit criteria
- Solution published
- Users have access
- Documentation available
- Release accepted

### Iterate
> Iterate as needed. New insights, user feedback, or changing requirements may require a return to Data Discovery (3), Design (4), or Build (5) before proceeding.

---

## 8. Handover
> Transfer the knowledge, responsibilities and assets needed for the client or receiving team to operate, maintain and improve the analytical solution.

### Activities
- Deploy or publish solution
- Configure access
- Complete release activities
- Communicate release
- Verify production operation

### Guidance
- ?

=== "Exploratory Analysis"
    - X
 
=== "Repeatable Analysis"
    - Y
 
=== "Model Development"
    - Z
 
=== "Dashboard & Reporting"
    - A

### Exit criteria
- Ownership assigned
- Knowledge transferred
- Support model agreed
- Project closed

### Additional
- Patterns written up and added to GHD wiki
