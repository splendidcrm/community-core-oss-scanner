# Threat model

## What this project does and where untrusted input enters
Full CRM web application for enterprise use, Rest.svc json api as well as Administration/Rest.svc json api

## Components that matter most / least
Rest APIs

## How to exercise it
Login: admin
Password: admin

## How you rate severity
API access to authenticated methods without authentication is severe.

## Anything to leave alone
Do not report CSS or HTML rendering errors
