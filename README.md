### What is this repository for?
This is for managing changes to support.gitlab.com 

### What do I need to use this?
- an API token (you'll need an admin to generate this for you)
- the `zendesk_apps_tools` gem
- this repository

### Getting started
- start by running `zat theme preview`
- Enter the appropriate subdomain, either `gitlab` for production or `gitlab1545832369` for sandbox
- your username will be your email address + `/token`, e.g. `jbloggs@gitlab.com/token`
- your password will be your API token

If all goes well, you can access the preview local changes using the link in your command line area that ends with `/start`.

After first time setup, if you want to change the subdomain to preview on the other instance. Check if you have a `.zat` file in your repo and rename or move it so that it will force ask you for the setup information again.

### What do I do if the changes are good?

- Push the changes to this repo with a MR for review
- After the the MR is merged to master, zip the repository.
- In Admin panel, [upload the repo as a new theme](https://support.zendesk.com/hc/en-us/articles/231747367-Changing-the-live-theme-of-your-Help-Center) and switch to it.

### Where can I get more info?
https://support.zendesk.com/hc/en-us/articles/115012793547-Using-local-theme-preview-Guide-Professional-
