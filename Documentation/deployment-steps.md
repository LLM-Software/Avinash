# Local Deployment:

- Postgres server deployment.
- Get database credentials.
- Within 'odoo.conf' at base directory, place:

        [options]
        db_user=root
        db_name=odoo_test
        db_password=****
        db_port=5432
        db_host=****

- Within working directory:

        python odoo-bin -i base
        python odoo-bin -i web

- Run server:

        python odoo-bin

- Create user by going to settings > user settings > new
- Setup apps by activating the apps in the home page.