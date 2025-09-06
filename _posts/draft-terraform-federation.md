Opinionated post about Terraform modules to support federation

Account-level terraform exposes groups and permissions via .tfvars files. Workspace admins can branch to request addition of groups to workspaces. Approvals on pull requests by account-team.

Similar pattern for workspace-level admins. Configure compute and workspace-level permissions via .tfvars files. Users can branch the repo to request changes to compute, etc. with approvals on pull request by workspace admin team. 

DABs run via CI/CD using service principal. Service principal permissions scoped to inside the workspace - no ability to change compute, etc.

Link to Alex Ott, etc.


