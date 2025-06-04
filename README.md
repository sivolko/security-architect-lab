# Cyber Security Architecture Lab

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Contributors](https://img.shields.io/github/contributors/your-org/azure-security-architecture-lab)](https://github.com/your-org/azure-security-architecture-lab/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/your-org/azure-security-architecture-lab)](https://github.com/your-org/azure-security-architecture-lab/issues)
[![Stars](https://img.shields.io/github/stars/your-org/azure-security-architecture-lab)](https://github.com/your-org/azure-security-architecture-lab/stargazers)

> A comprehensive repository for learning Azure security architecture through vulnerable scenarios and secure solutions.

## Project Structure 

azure-security-architecture-lab/
|
|-- README.md
|-- CONTRIBUTING.md
|-- LICENSE
|-- CODE_OF_CONDUCT.md
|-- SECURITY.md
|
|-- .github/
|   |-- ISSUE_TEMPLATE/
|   |   |-- bug_report.md
|   |   |-- feature_request.md
|   |   |-- new_scenario.md
|   |   |-- security_vulnerability.md
|   |
|   |-- workflows/
|   |   |-- documentation-check.yml
|   |   |-- link-checker.yml
|   |   |-- security-scan.yml
|   |   |-- auto-assign.yml
|   |
|   |-- PULL_REQUEST_TEMPLATE.md
|   |-- FUNDING.yml
|
|-- docs/
|   |-- README.md
|   |
|   |-- getting-started/
|   |   |-- README.md
|   |   |-- how-to-use-this-repository.md
|   |   |-- prerequisites.md
|   |   |-- learning-path.md
|   |   |-- quick-start-guide.md
|   |
|   |-- fundamentals/
|   |   |-- README.md
|   |   |-- zero-trust-principles.md
|   |   |-- defense-in-depth.md
|   |   |-- azure-security-services.md
|   |   |-- compliance-frameworks.md
|   |   |-- threat-modeling-basics.md
|   |
|   |-- architecture-patterns/
|   |   |-- README.md
|   |   |-- zero-trust-architecture.md
|   |   |-- defense-in-depth-pattern.md
|   |   |-- compliance-by-design.md
|   |   |-- multi-cloud-security.md
|   |   |-- critical-infrastructure.md
|   |   |-- supply-chain-security.md
|   |   |-- global-architecture.md
|   |
|   |-- implementation-guides/
|   |   |-- README.md
|   |   |-- assessment-methodology.md
|   |   |-- design-principles.md
|   |   |-- security-controls-mapping.md
|   |   |-- testing-and-validation.md
|   |   |-- deployment-automation.md
|   |
|   |-- compliance/
|   |   |-- README.md
|   |   |
|   |   |-- healthcare/
|   |   |   |-- README.md
|   |   |   |-- hipaa-implementation.md
|   |   |   |-- hitech-requirements.md
|   |   |   |-- fda-21-cfr-part-11.md
|   |   |
|   |   |-- financial-services/
|   |   |   |-- README.md
|   |   |   |-- pci-dss-implementation.md
|   |   |   |-- sox-compliance.md
|   |   |   |-- ffiec-guidelines.md
|   |   |
|   |   |-- government/
|   |   |   |-- README.md
|   |   |   |-- fedramp-implementation.md
|   |   |   |-- fisma-requirements.md
|   |   |   |-- nist-framework.md
|   |   |   |-- cmmc-compliance.md
|   |   |
|   |   |-- manufacturing/
|   |   |   |-- README.md
|   |   |   |-- iec-62443-implementation.md
|   |   |   |-- iso-27001-implementation.md
|   |   |
|   |   |-- privacy/
|   |       |-- README.md
|   |       |-- gdpr-implementation.md
|   |       |-- ccpa-compliance.md
|   |       |-- data-residency.md
|   |
|   |-- threat-intelligence/
|   |   |-- README.md
|   |   |-- threat-landscape.md
|   |   |
|   |   |-- industry-threats/
|   |   |   |-- healthcare-threats.md
|   |   |   |-- financial-threats.md
|   |   |   |-- government-threats.md
|   |   |   |-- manufacturing-threats.md
|   |   |   |-- education-threats.md
|   |   |
|   |   |-- attack-scenarios/
|   |   |   |-- ransomware-scenarios.md
|   |   |   |-- supply-chain-attacks.md
|   |   |   |-- insider-threats.md
|   |   |   |-- cloud-attacks.md
|   |   |
|   |   |-- threat-modeling/
|   |       |-- methodology.md
|   |       |-- stride-analysis.md
|   |       |-- attack-trees.md
|   |
|   |-- metrics-and-monitoring/
|       |-- README.md
|       |-- security-metrics.md
|       |-- compliance-reporting.md
|       |-- industry-benchmarks.md
|       |-- monitoring-strategies.md
|
|-- scenarios/
|   |-- README.md
|   |
|   |-- vulnerable/
|   |   |-- README.md
|   |   |
|   |   |-- basic/
|   |   |   |-- README.md
|   |   |   |
|   |   |   |-- 01-exposed-web-application/
|   |   |   |   |-- README.md
|   |   |   |   |-- architecture-diagram.md
|   |   |   |   |-- configuration.md
|   |   |   |   |-- security-issues.md
|   |   |   |   |-- attack-scenarios.md
|   |   |   |
|   |   |   |-- 02-poor-identity-management/
|   |   |   |   |-- README.md
|   |   |   |   |-- architecture-diagram.md
|   |   |   |   |-- configuration.md
|   |   |   |   |-- security-issues.md
|   |   |   |   |-- attack-scenarios.md
|   |   |   |
|   |   |   |-- 03-insecure-data-storage/
|   |   |   |   |-- README.md
|   |   |   |   |-- architecture-diagram.md
|   |   |   |   |-- configuration.md
|   |   |   |   |-- security-issues.md
|   |   |   |   |-- attack-scenarios.md
|   |   |   |
|   |   |   |-- 04-misconfigured-containers/
|   |   |       |-- README.md
|   |   |       |-- architecture-diagram.md
|   |   |       |-- configuration.md
|   |   |       |-- security-issues.md
|   |   |       |-- attack-scenarios.md
|   |   |
|   |   |-- enterprise/
|   |   |   |-- README.md
|   |   |   |-- 05-multi-region-enterprise/
|   |   |   |-- 06-zero-trust-remote-access/
|   |   |   |-- 07-multi-tenant-saas/
|   |   |   |-- 08-devsecops-pipeline/
|   |   |   |-- 09-iot-edge-computing/
|   |   |
|   |   |-- industry/
|   |       |-- README.md
|   |       |
|   |       |-- healthcare/
|   |       |   |-- 10-healthcare-cloud-migration/
|   |       |   |-- 20-pharmaceutical-research/
|   |       |
|   |       |-- financial/
|   |       |   |-- 11-high-frequency-trading/
|   |       |   |-- 18-retail-chain-integration/
|   |       |
|   |       |-- government/
|   |       |   |-- 12-defense-cloud/
|   |       |   |-- 19-aerospace-supply-chain/
|   |       |
|   |       |-- manufacturing/
|   |       |   |-- 13-smart-manufacturing/
|   |       |   |-- 17-energy-grid-protection/
|   |       |
|   |       |-- education/
|   |       |   |-- 16-educational-institution/
|   |       |
|   |       |-- media/
|   |           |-- 14-global-ecommerce/
|   |           |-- 15-content-protection/
|   |
|   |-- secure/
|       |-- README.md
|       |
|       |-- basic/
|       |   |-- README.md
|       |   |
|       |   |-- 01-secure-web-application/
|       |   |   |-- README.md
|       |   |   |-- architecture-diagram.md
|       |   |   |-- configuration.md
|       |   |   |-- security-controls.md
|       |   |   |-- implementation-guide.md
|       |   |   |-- validation-tests.md
|       |   |
|       |   |-- 02-secure-identity-architecture/
|       |   |-- 03-secure-data-storage/
|       |   |-- 04-secure-container-environment/
|       |
|       |-- enterprise/
|       |   |-- README.md
|       |   |-- 05-secure-multi-region-enterprise/
|       |   |-- 06-zero-trust-implementation/
|       |   |-- 07-secure-multi-tenant-saas/
|       |   |-- 08-secure-devsecops-pipeline/
|       |   |-- 09-secure-iot-edge/
|       |
|       |-- industry/
|           |-- README.md
|           |-- healthcare/
|           |-- financial/
|           |-- government/
|           |-- manufacturing/
|           |-- education/
|           |-- media/
|
|-- tools/
|   |-- README.md
|   |
|   |-- assessment/
|   |   |-- README.md
|   |   |-- security-checklist.md
|   |   |-- compliance-audit-template.md
|   |   |-- risk-assessment-matrix.md
|   |   |-- gap-analysis-template.md
|   |
|   |-- templates/
|   |   |-- README.md
|   |   |
|   |   |-- bicep/
|   |   |   |-- README.md
|   |   |   |-- networking/
|   |   |   |-- identity/
|   |   |   |-- storage/
|   |   |   |-- compute/
|   |   |
|   |   |-- terraform/
|   |   |   |-- README.md
|   |   |   |-- modules/
|   |   |   |-- examples/
|   |   |
|   |   |-- arm/
|   |   |   |-- README.md
|   |   |   |-- templates/
|   |   |
|   |   |-- powershell/
|   |       |-- README.md
|   |       |-- assessment-scripts/
|   |       |-- configuration-scripts/
|   |       |-- monitoring-scripts/
|   |
|   |-- policies/
|   |   |-- README.md
|   |   |-- security-policies/
|   |   |-- compliance-policies/
|   |   |-- custom-initiatives/
|   |
|   |-- monitoring/
|       |-- README.md
|       |-- azure-monitor/
|       |-- sentinel/
|       |-- workbooks/
|       |-- dashboards/
|
|-- examples/
|   |-- README.md
|   |
|   |-- quick-wins/
|   |   |-- README.md
|   |   |-- enable-mfa.md
|   |   |-- configure-nsg.md
|   |   |-- setup-key-vault.md
|   |   |-- enable-encryption.md
|   |
|   |-- step-by-step/
|   |   |-- README.md
|   |   |-- zero-trust-setup/
|   |   |-- sentinel-deployment/
|   |   |-- backup-strategy/
|   |   |-- disaster-recovery/
|   |
|   |-- real-world/
|       |-- README.md
|       |-- healthcare-implementation/
|       |-- financial-modernization/
|       |-- government-migration/
|       |-- manufacturing-transformation/
|
|-- resources/
|   |-- README.md
|   |
|   |-- architecture-diagrams/
|   |   |-- README.md
|   |   |-- visio-templates/
|   |   |-- draw-io-templates/
|   |   |-- mermaid-examples/
|   |   |-- powerpoint-templates/
|   |
|   |-- checklists/
|   |   |-- README.md
|   |   |-- pre-deployment-checklist.md
|   |   |-- post-deployment-checklist.md
|   |   |-- incident-response-checklist.md
|   |   |-- compliance-checklist.md
|   |
|   |-- playbooks/
|   |   |-- README.md
|   |   |-- incident-response-playbook.md
|   |   |-- vulnerability-management.md
|   |   |-- threat-hunting-playbook.md
|   |   |-- compliance-playbook.md
|   |
|   |-- reference-materials/
|       |-- README.md
|       |-- azure-security-benchmark.md
|       |-- cis-controls-mapping.md
|       |-- nist-framework-mapping.md
|       |-- industry-standards.md
|       |-- regulatory-requirements.md
|
|-- wiki/
|   |-- Home.md
|   |-- Quick-Start.md
|   |-- FAQ.md
|   |-- Troubleshooting.md
|   |-- Glossary.md
|   |-- Contributing.md
|
|-- assets/
    |-- images/
    |   |-- logos/
    |   |-- diagrams/
    |   |-- screenshots/
    |   |-- icons/
    |
    |-- videos/
    |   |-- demos/
    |   |-- tutorials/
    |
    |-- downloads/
        |-- templates/
        |-- tools/
        |-- guides/

## 🚀 Quick Start

1. **[Getting Started Guide](docs/getting-started/README.md)** - Start here if you're new
2. **[Quick Start Tutorial](docs/getting-started/quick-start-guide.md)** - 15-minute overview
3. **[Learning Path](docs/getting-started/learning-path.md)** - Recommended progression

## 📚 What's Inside

### 🚨 Vulnerable Scenarios
- [Basic Scenarios](scenarios/vulnerable/basic/) - Fundamental security issues
- [Enterprise Scenarios](scenarios/vulnerable/enterprise/) - Complex enterprise challenges
- [Industry Scenarios](scenarios/vulnerable/industry/) - Sector-specific vulnerabilities

### ✅ Secure Solutions
- [Secure Architectures](scenarios/secure/) - Corresponding secure implementations
- [Implementation Guides](docs/implementation-guides/) - Step-by-step guidance
- [Security Patterns](docs/architecture-patterns/) - Reusable security patterns

### 🏭 Industry Coverage
- 🏥 **Healthcare** - HIPAA, HITECH, FDA compliance
- 💰 **Financial Services** - PCI DSS, SOX, regulatory requirements
- 🏛️ **Government** - FedRAMP, FISMA, CMMC compliance
- 🏭 **Manufacturing** - OT/IT convergence, IEC 62443
- 🎓 **Education** - FERPA, student data protection
- 🎬 **Media & Entertainment** - Content protection, DRM

## 🛠️ Tools & Templates

- [Assessment Tools](tools/assessment/) - Security evaluation tools
- [Infrastructure Templates](tools/templates/) - Bicep, Terraform, ARM templates
- [Azure Policies](tools/policies/) - Security policy definitions
- [Monitoring Solutions](tools/monitoring/) - Monitoring and alerting configurations

## 📋 Compliance Frameworks

- [Healthcare Compliance](docs/compliance/healthcare/) - HIPAA, HITECH, FDA
- [Financial Compliance](docs/compliance/financial-services/) - PCI DSS, SOX, FFIEC
- [Government Compliance](docs/compliance/government/) - FedRAMP, FISMA, NIST
- [Privacy Regulations](docs/compliance/privacy/) - GDPR, CCPA, data residency

## 🎯 Learning Objectives

After using this repository, you will be able to:

- ✅ Identify common Azure security misconfigurations
- ✅ Design secure Azure architectures using best practices
- ✅ Implement industry-specific compliance requirements
- ✅ Apply zero-trust principles in Azure environments
- ✅ Conduct security assessments and threat modeling
- ✅ Automate security controls and monitoring

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Ways to Contribute
- 🐛 Report bugs or security issues
- 💡 Suggest new scenarios or improvements
- 📝 Improve documentation
- 🔧 Add new tools or templates
- 🎨 Create diagrams or visual content

## 📖 Documentation

- [📚 Full Documentation](docs/README.md)
- [🚀 Getting Started](docs/getting-started/README.md)
- [🏗️ Architecture Patterns](docs/architecture-patterns/README.md)
- [🔧 Implementation Guides](docs/implementation-guides/README.md)
- [📊 Metrics & Monitoring](docs/metrics-and-monitoring/README.md)

## 🏷️ Tags & Topics

`azure` `security` `architecture` `devops` `compliance` `zero-trust` `cloud-security` `enterprise` `healthcare` `financial-services` `government` `manufacturing` `education`

## ⚠️ Disclaimer

This repository contains deliberately vulnerable examples for educational purposes. **Never deploy vulnerable configurations in production environments.**

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details & Maintained by Shubhendu .

## 🙏 Acknowledgments

- Microsoft Azure Security team for guidance and best practices
- Community contributors who have shared their expertise
- Security researchers who have identified and documented vulnerabilities

---

**Star ⭐ this repository if you find it helpful!**
