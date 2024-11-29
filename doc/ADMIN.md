Unfortunately, for now, we can't automatically configure the app for you.  
So bear with us and:

- [Open your new InvoiceShelf instance](https://__DOMAIN__)
- Select your language of choice
- Click to check the requirements then click on "Continue"
- Click on "Continue" again to pass the permissions check
- Fill the database credentials with:
  - Database Connection: `pgsql`
  - Database Port: `5432`
  - Database Name: `__DB_NAME__`
  - Database Username: `__DB_USER__`
  - Database Password: `__DB_PWD__`
  - Database Host: `127.0.0.1`
- Let untick the overwrite option
- Click on "Save & Continue"
- Validate your domain name
  - If this step fails, please clear your cookies and try again or try with another browser
- Fill your mail credentials
  - To use the YunoHost mail system:
    - Choose "SMTP"
    - Mail Host: `localhost`
    - Mail Username: `__APP__`
    - Mail Passwword: `__MAIL_PWD__`
    - Mail Port: `25`
    - Mail Encryption: `null`
    - From Mail Address: `no-reply@__DOMAIN__`
    - From Mail Name: The name of your business
- Now you just have to complete the forms with your company details
