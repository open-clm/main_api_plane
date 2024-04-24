# main_api_plane
The main API plane through which the UI will be communicating to the backend with. These APIs are public facing in nature.
Following are the core feautures which are planned for each release:

## Prototype 0: v0.0.x
### 1. Lifecycle managament for Contracts:    [Figma] (✓)
- create (merge to master)
- delete (merge to master)
- update (merge to master)
- upload (merge to master)
- get
- search by title
- search by content
- esign??
### 2. Lifecycle management for Templates:    [Figma] (✓)
- create (merge to master)
- delete (merge to master)
- update (merge to master)
- upload (merge to master)
- get
- clone
- search by title
- search by content
- convert to contract
### 3. Lifecycle management for Drafts:       [Figma] (✓)
- create
- delete
- update
- upload
- get
- clone
- search by title
- search by content
- submit draft for review
- view submitted drafts
- revoke draft from review
### 4. Lifecycle management for Clausebooks
- create
- delete
- update
- upload
- search community
- download from community
- get
- search by title
- search by content
- clone
### 5. Discussions on any document:           [Figma] (✓)
- create
- delete
- update
- get
### 6. Review any document:                   [Figma] (✓)
- create
- delete
- update
- get
- approve
- reject
- threads
- add description
- add user to review
- remove user to review 
- discussion in thread #5
### 7. Create document metadata
- create tag
- delete tag
- update tag
- get all tags
- create key-value
- delete key-value
- update key-value
- get all key-value
- mark tag special (fixed meanings like `description`,`template blank descriptions`, `shared / private templates` for use in automations and plugins in later versions)
- mark key-value special (fixed meanings like `parties`, `risks` for use in automations and plugins in later versions)
### 8. Lifecycle management for Tasks
- create
- delete
- update
- get (includes all subtasks)
- add description
- add subtask
- update subtask
- delete subtask
- #5 discussion on subtask
- submit subtask??
- approve subtask submission
- reject subtask submission
### 9. Lifecycle management for users
- create
- delete
- update
- get
### 10. Lifecycle and access management for organizations
- create (with admin user)
- delete
- update
- get
- #users in organizations
- add permissions for document for user (permissions = edit, view, delete, etc)
- remove permissions for document for user

## Prototype 1: v0.x.x
1. Lifecycle management for Support Tickets
2. Lifecycle management for Automations
3. Creating the Automation Garage
4. Lifecycle management for Integrations
5. Creating the Integrations Marketplace
6. Improved notification management
7. Searching and sorting
8. Help
9. Tutorials
10. Hardening
11. Efficiency
12. Resiliency and SLA
