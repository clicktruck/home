# home

## Welcome

![clicktruck automation](docs/clicktruck.png)

The following grid represents the building blocks you may consider employing for:

* Provisioning cloud infrastructure and managed services
* Installing software via application templates

| Target Cloud | Packer | Terraform | Workflows |
| :--:  | :--:   | :--:      | :--:                    |
| AWS   | [:white_check_mark:](https://github.com/clicktruck/aws-packer) | [:white_check_mark:](https://github.com/clicktruck/aws-terraform) | [:white_check_mark:](https://github.com/clicktruck/aws-actions/actions) |
| Microsoft Azure | [:white_check_mark:](https://github.com/clicktruck/azure-packer) | [:white_check_mark:](https://github.com/clicktruck/azure-terraform) | [:white_check_mark:](https://github.com/clicktruck/azure-actions/actions) |
| Google Cloud  | [:white_check_mark:](https://github.com/clicktruck/google-packer) | [:white_check_mark:](https://github.com/clicktruck/google-terraform) | [:white_check_mark:](https://github.com/clicktruck/google-actions/actions) |
| Oracle Cloud | [:white_check_mark:](https://github.com/clicktruck/oracle-packer) | [:white_check_mark:](https://github.com/clicktruck/oracle-terraform) | [:construction:](https://github.com/clicktruck/oracle-actions/actions) |

| | Other resources |
| :--: | :--: |
| [:white_check_mark:](https://github.com/clicktruck/k8s-terraform) | Terraform for Helm deployments |
| [:construction:](https://github.com/clicktruck/application-templates) | Application Templates |
| [:construction:](https://github.com/clicktruck/platform-actions) | Platform Actions |
| [:white_check_mark:](https://github.com/clicktruck/scripts) | Platform scripts |

## Who is this for?

Operators, SREs, Security and Compliance, Developers with some background in public cloud and Kubernetes

## How might you exercise it?

In the context of evaluations, workshops, and PoCs

## Benefits

* For the community to perform quick evaluations
* Provisions all the underlying cloud infrastructure needed
  * e.g., Virtual networks, Kubernetes clusters, Container registries, DNS zones, Secrets management, Tools VM
* Installs either a single-cluster (full profile) or multi-cluster (build, iterate, view and run profiles) installation of Tanzu Application Platform
* Useful for setup and delivery of workshops or PoCs in client environments by field engineering
* Delivers a consistent experience for everyone involved
