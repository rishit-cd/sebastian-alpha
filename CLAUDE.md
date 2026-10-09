
# Project Instructions

## Technology
- Use Terraform for GCP infrastructure.
- Use Google Cloud Run, Cloud SQL, and GCS where appropriate.

## Security
- Follow least-privilege IAM.
- Do not hardcode passwords, API keys, or secrets.
- Prefer private networking for Cloud SQL.
- Do not make GCS buckets publicly accessible without approval.

## Terraform Rules
- Follow the existing module structure.
- Use variables instead of hardcoding environment-specific values.
- Run terraform fmt and terraform validate.
- Explain planned changes before applying infrastructure changes.

## Deployment
- Do not deploy to production without explicit approval.
- Use GitHub Actions for CI/CD.
