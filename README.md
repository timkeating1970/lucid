curl -O https://raw.githubusercontent.com/timkeating1970/lucid/main/lucid.yml
# This command allows you to grab the lucid.yml file from this repo and download to your local directory
# Launch in every account that you want to monitor (typically as a stackset in child accounts and as a stack in your payer account)

- Creating a new Lucidscale model > choose "Open Data Hub" > + New Account > Cross-Account Role > "Create a new Cross-Account Role"
- "Create a new role manually" > Take note of "Account ID: 799803075172" and External ID (which should change) e.g. cd7d3c5c-f17b-4733-8774-9d78d733125d
- lucid.yml is to be deployed as a stackset in every child account and as a stack in the payer account
- The Role ARN and Role name are then entered into the Lucidscale console
- You can then pull in the account into the Lucidscale console using the roles that were created
