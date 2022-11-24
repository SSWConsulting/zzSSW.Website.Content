# Overview 
This template provides users with a default set of issue templates and labels to work with.

## Issue Templates

To see the reasoning behind these issue templates see the rule:
https://www.ssw.com.au/rules/github-issue-templates

## Labels

To see the reasoning behind these labels refer to the rule: 
https://www.ssw.com.au/rules/labels-in-github

To add the default labels to your repo use Labeler. See Luke Parker's repo for instructions on how to set it up https://github.com/Hona/LabelTemplateRepository#readme

## Deployments

This repo calls the deployment pipeline on the [SSW.Website repository](https://github.com/SSWConsulting/SSW.Website).

In order to do this, a PAT has been generated for the SSW service account, and stored as a secret in this repository. This PAT has a 12 month expiry (expires 2 Nov 2023).
