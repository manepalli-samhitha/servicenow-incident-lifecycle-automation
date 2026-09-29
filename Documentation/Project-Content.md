# ServiceNow – Incident Lifecycle Automation

## Academic Structure

## 1. INTRODUCTION
### 1.1 Project Overview
This project demonstrates a ServiceNow Incident Management lifecycle using the scenario “Unable to connect to Corporate VPN from home office.”

### 1.2 Purpose
To document a structured incident-management workflow and its supporting ServiceNow records and validation points.

## 2. IDEATION PHASE
### 2.1 Problem Statement
An end user is unable to connect to the Corporate VPN from the home office. The incident requires structured classification, technical investigation, escalation, change-related action, resolution, and knowledge capture.

### 2.2 Empathy Map Canvas
End Users need timely resolution and visibility. Service Desk Agents need complete incident information and clear escalation paths. Level 2 Support needs accurate technical context, configuration-item information, knowledge, and related records. Change Management needs traceable change activity. The ServiceNow Administrator needs a structured, auditable lifecycle.

### 2.3 Brainstorming
The workflow uses Incident Management, Agent Assist, Knowledge Management, Change Management, CMDB, Related Records, Child Incidents, Watch List, Work Notes List, and SLA tracking.

## 3. REQUIREMENT ANALYSIS
### 3.1 Customer Journey Map
User report → Service Desk intake → classification → knowledge support → Network / Level 2 escalation → investigation → change-related handling → resolution → knowledge creation → final validation.

### 3.2 Solution Requirement
The solution must provide traceable incident intake, classification, escalation, knowledge integration, technical investigation, change-related handling, resolution documentation, knowledge creation, and final validation.

### 3.3 Data Flow Diagram
Caller → Service Desk → Incident → Classification / Service Mapping → Agent Assist / Knowledge → Network / Level 2 → Change-related activity → Resolution → Knowledge Article → Validation.

### 3.4 Technology Stack
ServiceNow ITSM with Incident Management, Service Catalog / Service Offering, Agent Assist, Knowledge Management, Change Management, CMDB, SLA / Task SLAs, Service Operations Workspace, Related Records and Child Incidents.

## 4. PROJECT DESIGN
### 4.1 Problem Solution Fit
The workflow connects the reported VPN issue to structured incident handling, escalation, technical investigation, change-related work, resolution, and knowledge reuse.

### 4.2 Proposed Solution
Use ServiceNow as the system of record for the incident lifecycle, with linked service, service offering, configuration item, knowledge, assignment, change-related and child records.

### 4.3 Solution Architecture
Caller → Service Desk → Incident → Knowledge / Agent Assist → Network / Level 2 → Change-related activity → Resolution → Knowledge Creation → Validation.

## 5. PROJECT PLANNING & SCHEDULING
### 5.1 Project Planning
Milestones: Incident Record Creation; Incident Classification; Knowledge Integration; Reassignment & Escalation; Change Request Creation; Child Incident Creation; Incident Resolution; Knowledge Creation; SLA & Related Record Validation.

## 6. FUNCTIONAL AND PERFORMANCE TESTING
### 6.1 Performance Testing
Validation focuses on correct record creation, field updates, assignment changes, knowledge integration, related-record linkage, resolution details, and SLA visibility. No unsupported numeric performance measurement is claimed.

## 7. RESULTS
### 7.1 Output Screenshots
The project evidence consists of the original screenshots supplied in this conversation and is organized by the lifecycle phase visible in each image.

## 8. ADVANTAGES AND DISADVANTAGES
### Advantages
Standardized incident handling, structured escalation, knowledge integration, change and related-record traceability, resolution documentation, SLA visibility, and multi-team collaboration.

### Disadvantages
Initial configuration requires manual setup; knowledge effectiveness depends on available articles; accurate CMDB data is required; change activities may introduce dependencies; agents require appropriate process knowledge.

## 9. CONCLUSION
The project documents a complete ServiceNow incident lifecycle for a Corporate VPN connectivity scenario, including creation, classification, knowledge integration, escalation, Level 2 investigation, change-related handling, resolution, knowledge creation, and final validation.

## 10. FUTURE SCOPE
Automated escalation, enhanced AI-powered Agent Assist, predictive analytics, customer self-service, monitoring integrations, chatbot-assisted classification, and advanced reporting.

## 11. APPENDIX
### Source Code
No source-code component was supplied for this ServiceNow workflow project.

### Dataset Link
No external dataset was supplied.

### GitHub & Project Demo Link
Repository: https://github.com/manepalli-samhitha/servicenow-incident-lifecycle-automation  
Demo: No screen-recording link was supplied.

## Project Scenario Details
- Service: Remote Access
- Service Offering: Corporate VPN
- Incident scenario: Unable to connect to Corporate VPN from home office
- Caller: Michael Hoefer
- Initial Assignment Group: Service Desk
- Category: Network
- Subcategory: VPN
- Channel: Phone
- Urgency: 2 - Medium
- Configuration Item: ThinkStationS20 initially, later updated to PowerEdge
- Network assignment: Network
- Level 2 user: David Loo
- On Hold Reason: Awaiting Change
- Probable Cause: PowerEdge service was suspended and required restart.
- Resolution Code: Workaround provided
- Resolution Notes: Restarted VPN-SRV-02 service as per emergency change request.
- Knowledge Base: IT
- Template: Standard

## Workflow Documentation
1. **Service Creation** — Configure Remote Access.
2. **Service Offering Creation** — Configure Corporate VPN under Remote Access.
3. **Incident Record Creation** — Create the VPN incident for Michael Hoefer and initially assign it to Service Desk.
4. **Incident Classification** — Set Phone, Network, VPN, urgency 2 - Medium, and service mapping.
5. **Agent Assist** — Search Knowledge Articles using the incident context.
6. **Knowledge Article Helpful / Attach** — Mark the relevant article Helpful and attach it with the supplied comment.
7. **Watch List / Work Notes List** — Add Samantha Bordwell to Watch List and Beth Anglin to Work Notes List.
8. **Reassignment to Network** — Reassign the incident to Network.
9. **Level 2 Investigation** — David Loo investigates and reviews incident, knowledge, SLA, and related records.
10. **Configuration Item Update** — Change the CI from ThinkStationS20 to PowerEdge.
11. **On Hold – Awaiting Change** — Set the incident On Hold with the supplied reason.
12. **Child Incident Creation** — Create and link the related child incident.
13. **Cause Documentation** — Record the supplied probable cause.
14. **Resolution Documentation** — Record the supplied resolution code and notes.
15. **Incident Resolution** — Resolve the incident after the documented action.
16. **Knowledge Article Creation** — Create knowledge using IT and Standard.
17. **SLA Validation** — Review available SLA information.
18. **Related Records Validation** — Verify linked records.
19. **Final End-to-End Validation** — Verify the complete lifecycle.