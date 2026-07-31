# Cloud Engineering Toolkit

**A free, single-file, browser-based reference and generator toolkit for cloud engineers working across Azure, AWS, and GCP.**

Live: https://headspace222.github.io/cloud-engineering-toolkit/

No build step, no dependencies, no sign-up. Open it in a browser and it works.

## What's Inside

- **Multi-Cloud (8 tools)** - side-by-side reference and conversion tools spanning all three major providers
- **Networking (5 tools)** - CIDR and subnet calculations, security/firewall rule generation
- **Infrastructure as Code (6 tools)** - Terraform backend generators for Azure Blob Storage, AWS S3+DynamoDB, and GCP Cloud Storage; resource naming convention generators following Azure CAF, AWS, and GCP standards
- **Kubernetes (4 tools)** - Deployment manifest generator with resource requests/limits, readiness/liveness probes, and security context baked in by default
- **Scripting (4 tools)** - a Bash snippet library indexed by cloud provider and task
- **Cost (3 tools)** - cost-related reference and estimation tools
- **Reference** - a searchable cross-cloud CLI command table, mapping the same operation across Azure CLI, AWS CLI, and gcloud side by side

## Why This Exists

Working across multiple clouds means constantly switching mental models and remembering three different CLI syntaxes, three different naming conventions, and three different ways to write the same firewall rule. This toolkit exists to collapse that friction into one page: pick a task, get the output in the format and cloud you actually need, copy it, move on.

Every generator produces real, usable output - actual Bicep, ARM JSON, Terraform HCL, az/aws/gcloud CLI commands, and Kubernetes YAML - not placeholder examples.

## Tech

Plain HTML, CSS, and JavaScript. No frameworks, no build tooling, no external runtime dependencies beyond Google Fonts. Deployed as a static site via GitHub Pages directly from this repository.

## Part of a Broader Portfolio

This toolkit sits alongside a ten-project Azure cloud engineering portfolio covering identity governance, security, networking, observability, and CI/CD - see the full list on my GitHub profile: https://github.com/headspace222

## Connect

Jane Ologhadien - Cloud & Infrastructure Engineer
LinkedIn: https://www.linkedin.com/in/jane-ologhadien-5b03ba12b