Creates an environment by uploading a blueprint, creating a deployment and running the `install` workflow.

# Prerequisites

## Environment Variables

This Action uses the Cloudify Profile environment variables described in the official
Cloudify documentation (see [More Information](#more-information) below).

# Inputs

(Certain commonly-used inputs are documented in our official website; see [More Information](#more-information) below)

Name | Description
-----|------------
`blueprint` | Path/URL to blueprint (YAML file or archive file)
`inputs-file` | Path to YAML/JSON inputs file

# More Information

Refer to [Cloudify CI/CD Integration](https://docs.cloudify.co/latest/working_with/integration/) for additional information about
Cloudify's integration with CI/CD tools.
