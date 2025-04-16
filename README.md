# .github

# HMPM – Heimerle Meule Precious Metals

Welcome to the official GitHub organization of **HMPM – Heimerle Meule Precious Metals**.

This organization serves as the central platform for our internal applications, infrastructure as code, DevOps automation, and collaborative development across the HMPM Group.

---

## 👥 Organization & Contacts

**Organization Owners**  
- Atilla Özyurt – [atilla.oezyurt@hm-pm.com](mailto:atilla.oezyurt@hm-pm.com)  
- Andreas Unselt – [andreas.unselt@hm-pm.com](mailto:andreas.unselt@hm-pm.com)

If you have any questions regarding repository access, workflows, or onboarding, feel free to contact us.

---

## 🔐 Access & SCIM Integration

User and group management is synchronized automatically via **Azure Entra ID (SCIM)**.  
Access is governed by role-based group assignments (`az-rbac-github-*`) within our Azure tenant.

Please make sure your Azure account is correctly assigned to the appropriate team or application group to gain access.

---

## 📁 Repository Structure

We organize our repositories into the following categories:

- **Applications**: Internal business apps (e.g. *Blaue Mann*, *Grüne Mann*, *Scrapp*, etc.)
- **Infrastructure**: Terraform modules, Azure resources, Kubernetes deployments
- **DevOps & Monitoring**: CI/CD workflows, Helm charts, Grafana dashboards
- **Shared Modules**: Libraries, components, templates, and reusable code

---

## ✅ Guidelines

- 🔒 **Access Control**: All access is managed via Azure AD group membership.
- 🚀 **CI/CD Pipelines**: Pipelines are triggered through GitHub Actions. Pull Requests are mandatory for all changes.
- 🧪 **Testing & Deployment**: Code is tested in dev/stage environments before production rollout.
- 📄 **Documentation**: Look for a `README.md` or `docs/` folder within each repository for more information.

---

## 🌐 Additional Information

This GitHub organization is part of our digital strategy and will evolve continuously. We value collaboration, transparency, and secure development practices.

---

**Last updated**: _April 2025_
