# Organizations and Domains

This repository contains a list of curated domains and organizations. For each of these organizations, one or more domains are provided and each domain is followed by an attribute to state the top level of such domain.

Affiliation of open source contributions is a hot topic within the CHAOSS community, but in some others as well using other toolchains beyond CHAOSS. This file aims at being a centralized key piece of information for anyone interested in affiliating contributions based on domain information used by the participants in a community.


## Organizations file format

The format of this file is JSON and this is as follows:

```
{
    "organizations": {
        "Organization A": [
            {
                "domain": "a.com",
                "is_top": true
            }
        ],
        "Organization B": [
            {
                "domain": "b.org",
                "is_top": true
            }
        ]
    }
}
```

This is initially based on the [SortingHat](https://github.com/chaoss/grimoirelab-sortinghat]) format.

# How can you help?

If you are aware of a non-listed organization, wrong domains, extra domains, or any other issue, you are more than welcome to send a pull request. And we all will be happy about reviewing and integrating this into the final file.
