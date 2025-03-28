# Continuous Reporting Community Working Group Plan

## Table of Contents 
- [Background](#background)
- [The Continuous Reporting Community Working Group](#the-continuous-reporting-community-working-group)
    - [Participation](#participation) 
    - [Key Community Working Groups Activities](#key-community-working-groups-activities)
    - [Interaction with FedRAMP](#interaction-with-fedramp)
    - [Transparency and Communication](#transparency-and-communication)
    - [Changes to CWG Operations](#changes-to-cwg-operations)

## Background
FedRAMP Community Working Groups (CWGs) are public, informal, and collaborative groups that facilitate industry-led knowledge sharing on best practices for information security of cloud services. FedRAMP will rely on the direct engagement provided by CWGs to ensure a smooth transition towards its updated mission of setting policies that enable private innovation to provide solutions to information security problems.

Every FedRAMP CWG has the following primary objectives:
1. Ensure FedRAMP has direct insight into community activities, goals, achievements, best practices, etc. in specific areas to inform creation of policies prior to their formal development.
2. Ensure that FedRAMP stakeholders have equal public access to information from FedRAMP and an open forum and semi-structured opportunities to work towards shared goals in different and innovative ways.



## The Continuous Reporting Community Working Group
The Continuous Reporting CWG is focused on communicating risk. They will identify effective ways for CSPs to communicate their ongoing risk posture, incidents, and continuous improvement activities with agencies and other customers. They will also identify opportunities for communication via automation and create specifications for communicating ongoing secure decisions enforcement by each CSP. The CWG will explore future models where CSPs are able to continuously represent their risk posture via an ongoing, data-driven ratings rather than gating mechanisms, enabling non-blocking changes while maintaining visibility.

In the future, ongoing risk monitoring will be enforced, validated and reported by continuous technical validation. CSPs will have a transparent, effective methodology for reporting overall risk posture and incident status via standard customer channels without FedRAMP in the middle.


The following areas are in scope:
- **Data generation:** data is automatically generated from system components (CI/CD, monitoring agents, vulnerability scans, configurations, etc.)
- **Data analysis:** data is normalized and aggregated to transform into information in the form of Key Security Indicators (KSIs) that represent system risk
- **Reporting:** Information is presented to customers in consolidated reports or dashboards that reflect near-real time risk posture, enabling informed, risk based decision making

The scope of the Continuous Reporting CWG is the *who*, *what*, *when*, *where*, and *how* for the above areas. The scope of the Continuous Reporting CWG does not include the development of official FedRAMP policies.


### Participation
FedRAMP CWGs are open to the public and all members of the community may participate or follow along. 

The Continuous Reporting CWG is especially relevant for members of the following communities:

- Security & compliance practitioners
- Engineers
- Cybersecurity experts
- Agency leaders
- 3PAOs


### Key CWG Activities
FedRAMP advocates may mediate discussion on specific topics of interest to FedRAMP but participants are strongly encouraged to self-organize around activities related to the CWG.

**Produce a Methodology for CSPs to Continuously Report Risk**
- Initial Outcome: No later than the conclusion of the first two meetings, create and approve a project plan with overall direction including outcomes, timelines, and milestones

- Strategic Outcome: Continuous Risk Reporting Methodology: Produce specifications for a workable methodology that uses a streamlined, data driven approach to risk reporting. Provide insight into best practices for reporting and communicating security incidents. Provide insights into generating, measuring, and communicating uniform baseline key security indicators (KSIs) that facilitate objective comparison across cloud services while allowing for flexible community-driven extensions. Provide insights into enabling non-blocking changes while maintaining appropriate security visibility and risk awareness for customers.

**Strengthen Collaboration Between FedRAMP and the Private Sector**
- Ensure FedRAMP has direct insight into community activities, goals, achievements, and best practices to inform the creation of policies prior to their formal development.
- Ensure FedRAMP stakeholders have equal, public access to information from FedRAMP, an open forum, and semi-structured opportunities to work towards shared goals in innovative ways.
- Foster a culture/creating a framework where compliance augments security instead of being a roadblock
- Explore approaches to help customers interpret security information and make risk-based decisions using new control validation and reporting models.
The Continuous Reporting CWG may involve the following activities:

**GitHub Based Collaboration**
- Maintain a GitHub-based discussion forum where the Community Working Group can collaborate in public (GitHub is chosen because it is an approved GSA cloud service offering that provides community capabilities and is open to use by the public for free. GSA does not have an alternative that meets this criteria). 

**Creation of Supporting Artifacts**
- As necessary, create and maintain code or example architectures that support automated continuous reporting (markdown reporting formats, etc.)


### Interaction with FedRAMP
The Continuous Reporting CWG will be mediated by the following member of the FedRAMP PMO:
- John Hamilton [@JohnWHamilton](https://www.github.com/JohnWHamilton)

Community working group mediators are PMO participants responsible for administrative tasks and connective tissue. They will:
  - Provide general working group facilitation, ensuring folks stay on track with the agenda, and that everyone is able to participate appropriately.
  - Schedule meetings and post a public calendar, ensure agendas are developed, the meeting platform works appropriately, and notes are captured and posted.
  - Occasionally pose questions to the group in a way that is clearly designed to spark general discussion around a topic to see individual opinions and responses.

In addition, the following members of the FedRAMP PMO will support this community as FedRAMP advocates, sharing additional information and addressing feedback as appropriate:
- AJ Stein [@aj-stein-gsa](https://www.github.com/aj-stein-gsa)
- Sam Aydlette [@sam-aydlette](https://www.github.com/sam-aydlette)

FedRAMP Advocates are PMO folks engaging with the CWGs and advocating for FedRAMP in them, with a focus on technical content. They will:
  - Answer questions related to how FedRAMP’s policies can best be informed by the activities performed in the working group.
  - Clarify FedRAMP’s goals and objectives related to the development of policies.
  - Share public prototypes, examples, sample code, etc. developed by FedRAMP to be placed in the public domain.
  - Contribute to the development of additional public prototypes, examples, sample code, etc. developed by participants of the working group where that work is public and contributions will remain in the public domain.

All communication related to this community must take place in public; private messages and emails related to this community will be ignored by the Community Mediator and FedRAMP advocates. Industry professionals should be aware there are limitations on how the federal government and its representatives can engage in CWGs. FedRAMP will not manage or control the CWGs activities, nor will we use working groups to seek consensus advice, review, or approval.
FedRAMP’s Disclaimer of Liability and Endorsement applies to all activity from government representatives participating in the CWG: [FedRAMP Disclaimer](https://fedramp.gov/disclaimer)


### Transparency and Communication
This CWG will primarily operate on GitHub in the following repository and Discussion forum:
- [GitHub Repository](https://github.com/FedRAMP/reporting-continuously/tree/main)
- [Discussion Forum](https://github.com/FedRAMP/continuous-reporting-cwg/discussions)

The community mediator will host regular town halls for managed discussion, updates, and Q&A:
- [Zoom signup link](https://gsa.zoomgov.com/meeting/register/t7WXSUz2SqK7Pdn8KXH8jQ#/registration)

Recordings from each town hall will be publicly posted on FedRAMP’s YouTube channel as follows:
- [FedRAMP Youtube Channel](https://www.youtube.com/@FedRAMP)

Every two weeks, the community mediator will post a Summary of Activity to the CWG that includes the following:
- Recap of questions asked by FedRAMP
- Recap of major topics of discussion
- Recap of major topics from the weekly town halls
- Errata or updates as appropriate
- Expected topics of focus for the next two weeks


### Changes to CWG Operations
FedRAMP Community Working Groups are a new idea that will need to be continuously and incrementally improved. FedRAMP is committed to supporting CWGs throughout the development of FedRAMP 20x and will provide clear instructions at least thirty days in advance of any significant changes to each CWG.
