# Currently Supported Indicators Types:

- IP

![](media/ip_indicator.png)

- URL

![](media/url_indicator.png)

- Hashcode

![](media/hash_indicator.png)

- Domain

![](media/domain_indicator.png)

# Deployment:

- If you have the default IR content pack, you will need to disable the equivalent playbooks:
    - Indicator (Type Domain) - Get Reputation
    - Indicator (Type MD/SHA1/SHA256) - Get Reputation
    - Indicator (Type IP) - Get Reputation
    - Indicator (Type URL) - Get Reputation
- Import the playbook collection Alt-Enrich-Collection.json (available here)
- Activate the playbooks provided in this content pack
