---
title: Terraform deployment on {{ env.ENVIRONMENT }} environment
labels: terraform
---
Deployment details:

```json
{
    "sha": "{{ env.GITHUB_SHA }}",
    "environment": "{{ env.ENVIRONMENT }}"
}
```
