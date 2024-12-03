# checkov-action

Github action for running the Checkov against terraform code

# Usage
```yaml
- name: Run Checkov
- uses: rkr-projects/checkov-action@V1.0
```

# Inputs
| Input Name               | Description              | Type     | Required | Default |
|--------------------------|--------------------------|----------|----------|---------|
| infrastructure-directory | Infrastructure directory | `string` | No       | `.`     |
