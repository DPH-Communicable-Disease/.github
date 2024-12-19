Procedure for Managing GitHub at DPH
Purpose
This document outlines the procedures for managing the North Carolina Division of Public Health’s GitHub repository, including access, moderation, ownership, and other key responsibilities. The goal is to ensure data security while at the same time providing a public benefit from code sharing. 

1. Account Usage and general responsibilities
* GitHub Account: Employees must use their DHHS email to create Github accounts. These accounts must be used when working on or contributing to the state health division’s public repository. GitHub accounts using personal email addresses should not be used.
* Github administrators: Manage repository settings, approve major changes, and ensure smooth operations. Responsible for the technical aspects of the repository, including code review and approval of contributions. Administrators oversee the overall strategy and compliance of GitHub repository usage.
* Contributors: Upload and maintain code and documentation, ensuring it aligns with division goals and standards.
* DPH is responsible for management. Auditing and administrating tasks. 
2. Repository Access and Permissions
* Public Access: The repository is public, and anyone on the internet can view the code. However, only approved personnel may upload, modify, or approve changes.
* Contributors: A designated list of contributors (employees approved by administrators) will have "write" access to the repository, allowing them to push changes or create pull requests. Initially there will only be a handful of contributors. 
* Administrators: A smaller group of administrators will be responsible for managing repository settings, merging code, and overall moderation. When an employee leaves the division or transitions out of relevant duties, their access will be promptly revoked, and permissions will be reassigned as needed.
3. Code Contribution and Approval Process
* Submission of Code: Any code or documentation to be uploaded must first be reviewed by a contributor. Only code that passes the review process can be uploaded to the public repository.

4. Code governance: contributors will review the code in the following areas:
* This section needs to be developed. 
* Accuracy: Ensuring that the code performs as intended and yields reproducible results.
* Compliance: Ensuring that all contributions comply with legal, privacy, and data-sharing regulations.
* No Sensitive Data: No personal, identifiable, or sensitive health data should be posted to the public repository. Only anonymized, aggregate-level data may be shared where relevant.
* Code Only: The repository will house code, documentation, and non-sensitive datasets or examples for reproducibility. 
* No Third-Party Libraries or Code: To reduce legal liability, no third-party libraries, tools, or external code will be uploaded or incorporated into the repository. All code must be written internally by employees of NC DPH.
* No PHI. 
* Original Code Requirement: Contributors must ensure that all code in the repository is original and owned by the division.
* Version Control: All code will be version-controlled using Git. Employees are required to follow GitHub best practices, including descriptive commit messages and adherence to branch workflows.
* Dual audit approval. Two different people. Cannot be contributor and approver. 
* No file paths. Use relative paths. Use here package in R. 
5. Ownership of Code
* Intellectual Property: All code and documentation posted to the GitHub repository is owned by NC DPH. Employees contributing to the repository understand that their work is a product of their role within the division and belongs to the division, not individual employees.
6. Liability Disclaimer
* Content Responsibility: The state health division assumes responsibility for the content uploaded to the public GitHub repository. Any code or analysis published reflects the official work of the division.
* Liability Clause: Although the code is publicly shared for transparency and reproducibility, no guarantees are made regarding its accuracy or fitness for any particular purpose. The division disclaims liability for any harm caused by the use of the content.
* External Use: While external parties are free to use and adapt the code, they do so at their own risk. The division is not liable for any unintended consequences from the use of the code by third parties.
7. Repository Maintenance and continuity
* Ongoing Maintenance: The repository should be regularly maintained to ensure that the code remains relevant and functional. Obsolete or deprecated code should be clearly labeled or removed.
* Documentation: Contributors are required to maintain clear documentation for all code uploaded. This includes details on functionality, dependencies, and instructions for use.
* Handling Transitions: If the main administrator or a key contributor leaves the division, their responsibilities must be formally transferred to another qualified team member.
o Access Transfer: The exiting person’s GitHub permissions will be immediately revoked, and a successor will be appointed to manage the repository.
o Handover of Responsibilities: A comprehensive handover document should be prepared, including current state of the repository, pending issues or updates, and instructions for repository management
* Backup Procedures: Regular backups of the repository (code and documentation) should be made to an internal, secure location to ensure continuity of access if needed.
