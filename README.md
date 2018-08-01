# Tested DC/OS OSes GCP

This is a module that properly configures the DC/OS prerequisites for selected OSes on top of GCP.

## EXAMPLE

```hcl
module "dcos-tested-gcp-oses" {
   source   = "./modules/dcos-tested-gcp-oses"
   os       = "${var.os}"
}
```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| os | OS name_version | string | - | yes |

## Outputs

| Name | Description |
|------|-------------|
| gcp_image_family | GCP Image Family Name |
| gcp_image_name | GCP Image Name |
| os-setup | Main Output |
| user | Output |

## Roadmaps

 - [ ] Add DC/OS version support pre-req instructions
