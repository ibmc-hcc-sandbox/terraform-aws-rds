apiVersion: backstage.io/v1alpha1
kind: Component
metadata:
  name: aws-terraform-module-rds
  title: Terraform Module to Deploy AWS RDS
  language: terraform
  description: |
    This Terraform automation creates and manages the RDS
  annotations:
    github.com/project-slug: ibmc-hcc-sandbox/terraform-aws-rds
    backstage.io/techdocs-ref: dir:.
  tags:
    - terraform
    - aws
    - rds

spec:
  type: service
  owner: Platform-Engineering-Services/terraform-code-managers
  lifecycle: production
