# CoNeCo Research Laboratory
# GitHub Organization Access Matrix

**Document Version:** 1.0  
**Last Updated:** July 2026

---

# Purpose

This document defines the standard access permissions for members of the CoNeCo Research Laboratory GitHub Organization.

The objective is to:

- Protect research outputs
- Maintain repository consistency
- Support collaboration
- Apply the Principle of Least Privilege
- Ensure proper governance of public research datasets and software

Repository maintainers should follow this document when assigning permissions to organization members.

---

# Organization Roles

The GitHub Organization is divided into the following teams:

- Leadership
- Research Staff
- Students
- Collaborators

Membership should be reviewed periodically by the Principal Investigator (PI).

---

# Permission Levels

GitHub permissions are assigned at the repository level.

| Permission | Description |
|------------|-------------|
| **Admin** | Full administrative control of a repository, including repository settings, permissions, releases, and branch protection. |
| **Maintain** | Manage repository contents, releases, issues, and pull requests without modifying sensitive administrative settings. |
| **Write** | Create branches, upload files, commit changes, and contribute documentation. |
| **Read** | View and download repository contents without modifying them. |

---

# Team Access Matrix

| Team | Typical Members | Repository Permission | Primary Responsibilities |
|------|-----------------|----------------------|--------------------------|
| **Leadership** | Principal Investigator (PI), Co-PI, Laboratory Director | **Admin** | Repository governance, publication approval, repository administration, member management |
| **Research Staff** | Research Assistants, Laboratory Engineers | **Maintain** | Repository maintenance, documentation review, dataset publication, release management |
| **Students** | Undergraduate Researchers, Graduate Students, Thesis Students | **Write** | Upload datasets, documentation, scripts, and supporting materials |
| **Collaborators** | External Researchers, Visiting Faculty, Industry Partners | **Read** | Review, download, and cite published research outputs |

---

# Responsibility Matrix

| Activity | Leadership | Research Staff | Students | Collaborators |
|-----------|:----------:|:--------------:|:--------:|:-------------:|
| View repository | ✓ | ✓ | ✓ | ✓ |
| Clone/download repository | ✓ | ✓ | ✓ | ✓ |
| Create branches | ✓ | ✓ | ✓ | ✗ |
| Commit changes | ✓ | ✓ | ✓ | ✗ |
| Upload datasets | ✓ | ✓ | ✓ | ✗ |
| Edit documentation | ✓ | ✓ | ✓ | ✗ |
| Create Releases | ✓ | ✓ | ✗* | ✗ |
| Manage Issues | ✓ | ✓ | ✓ | ✗ |
| Manage Pull Requests | ✓ | ✓ | ✓ | ✗ |
| Configure repository settings | ✓ | Limited | ✗ | ✗ |
| Manage repository permissions | ✓ | ✗ | ✗ | ✗ |
| Delete repository | ✓ | ✗ | ✗ | ✗ |

\* Students may create releases only with approval from the repository maintainer or PI.

---

# Organization Owners

Organization Owners have administrative control over the GitHub Organization itself.

Responsibilities include:

- Creating repositories
- Managing organization settings
- Creating and managing teams
- Assigning repository permissions
- Managing billing (if applicable)
- Configuring security settings
- Managing organization membership

For security reasons, the number of Organization Owners should be kept to a minimum.

Recommended:

- Principal Investigator
- Laboratory Administrator or Senior Research Assistant

---

# Permission Assignment Guidelines

## Leadership

Leadership members are responsible for the overall governance of the laboratory's GitHub Organization.

Admin access should only be granted to trusted personnel responsible for repository administration and publication approval.

---

## Research Staff

Research Staff maintain repositories on behalf of the laboratory.

Typical responsibilities include:

- reviewing repository documentation
- organizing datasets
- publishing releases
- maintaining metadata
- reviewing student submissions

Research Staff should not modify repository permissions unless specifically authorized.

---

## Students

Students contribute research outputs to repositories associated with their projects.

Students are expected to:

- follow laboratory repository standards
- complete required documentation
- maintain data quality
- update the repository README
- complete metadata

Students should not change repository settings.

---

## Collaborators

Collaborators are generally granted read-only access.

If a collaborator actively contributes to a project, temporary Write or Maintain access may be granted for that specific repository with approval from the PI.

---

# Principle of Least Privilege

Members should receive only the permissions necessary to perform their responsibilities.

Additional permissions should be granted only when justified by project requirements.

---

# Repository-Specific Exceptions

Project-specific repositories may require different permissions.

Examples include:

- Industry-funded projects
- Confidential research
- Multi-university collaborations
- Active software development

Any exceptions should be approved by the Principal Investigator.

---

# Review of Permissions

Organization membership and repository permissions should be reviewed:

- at the beginning of each academic year
- after project completion
- when members graduate or leave the laboratory
- whenever organizational responsibilities change

Inactive members should be removed promptly to maintain repository security.

---

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | July 2026 | Initial release |
