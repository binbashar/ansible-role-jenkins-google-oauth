# Ansible Role: Binbash Jenkins Google OAuth

Ansible role for installing and configuring Google OAuth on Jenkins

## Requirements
* Jenkins with Google OAuth plugin installed => https://plugins.jenkins.io/google-oauth-plugin/

## Examples
```
  - role: binbash_inc.jenkins-google-oauth
    jenkins_google_oauth_client_id: "your-google-oauth-client-id"
    jenkins_google_oauth_client_secret: "your-google-oauth-client-secret"
    jenkins_google_oauth_domain: "your-google-oauth-domain"

```
