# Azure-Governance-with-IaC

# Problem:
In many organizations, manual cloud resource deployment can lead to human error, security vulnerabilities, and inconsistent configurations. The goal of this project was to address this by building a secure, consistent, and fully governed Azure environment using Infrastructure as Code (IaC). The project demonstrates a proactive approach to cloud administration, focusing on security, governance, and automation.
# Solution
This project uses Azure Bicep to deploy a foundational, secure environment in a single, repeatable action. The solution includes the following key components:

Azure Key Vault: A dedicated vault for securely storing sensitive data, such as administrator passwords and connection strings. Access to the vault is managed through Role-Based Access Control (RBAC) to ensure a principle of least privilege.

Virtual Machine (VM): A basic Linux virtual machine is deployed to serve as a testbed for applications or services.

Network Configuration: The VM is configured with a public IP address and a Network Security Group (NSG) to control inbound SSH access, securing the network perimeter.

Proactive Governance: An Azure Policy is assigned to the subscription to enforce rules, such as restricting resource deployment to a specific region, preventing costly mistakes and ensuring compliance.

# Result
By automating the deployment of this environment with Bicep, I demonstrated proficiency in several core Azure administrator skills:

Infrastructure as Code (IaC): The ability to provision and manage cloud resources programmatically, ensuring consistency and repeatability.

Security: Implementation of a dedicated Key Vault and network security rules to protect sensitive data and network access.

Governance: Proactive enforcement of company policies using Azure Policy, demonstrating a commitment to compliance and cost management.

Resource Management: A clean and organized deployment that can be easily scaled or torn down, showcasing efficient management practices.

This project is not only a functional cloud environment but a testament to a modern, automated approach to cloud administration.

# Repository Contents:

main.bicep: The Bicep template used to deploy all resources.

README.md: This project documentation.

Screenshots of services used & deployed resources
