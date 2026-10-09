
---
name: terraform-security-review
description: Review Terraform code for GCP security issues, least privilege, and compliance before deployment.
---

# Terraform Security Review

When reviewing Terraform code:

1. Check for overly broad IAM permissions, such as Owner or Editor.
2. Check that Cloud SQL uses private IP and SSL where required.
3. Check that GCS buckets do not allow public access.
4. Check that secrets are not hardcoded in Terraform files.
5. Check that resources have appropriate labels.
6. Report findings by severity: Critical, High, Medium, Low.
7. Suggest fixes and show corrected Terraform code.
8. Do not modify files or deploy changes unless explicitly asked.
