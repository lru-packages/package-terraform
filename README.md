# package-terraform

Terraform provides a common configuration to launch infrastructure — from physical and virtual servers to email and DNS providers. Once launched, Terraform safely and efficiently changes infrastructure as the configuration is evolved. Simple file-based configuration gives you a single view of your entire infrastructure. <https://www.terraform.io>

See <https://github.com/hashicorp/terraform/releases> for releases.

## Generating the RPM package

Edit the `Makefile` to ensure that you are setting the intended version, then run `make`.

```bash
make
```
