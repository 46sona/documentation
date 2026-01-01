# documentation
## Gitea Mail Configuration (Docker Compose)

Gitea email notifications were configured using Gmail SMTP.
The configuration is defined using environment variables inside a Docker Compose file.

### Mailer Environment Variables

- GITEA__mailer__ENABLED=true  
- GITEA__mailer__PROTOCOL=smtps  
- GITEA__mailer__SMTP_ADDR=smtp.gmail.com  
- GITEA__mailer__SMTP_PORT=465  
- GITEA__mailer__USER=<gmail-id>  
- GITEA__mailer__PASSWD=<gmail-app-password>  
- GITEA__mailer__FROM=<gmail-id>  
- GITEA__mailer__TLS=true  

This setup enables secure email notifications using Gmail App Password authentication.

