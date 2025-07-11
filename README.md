```bash
#################################################################
#     ____  __  ____  ___   __   __________  ____  __  ______   #
#    / __ )/ / / / / / / | / /  / ____/ __ \/ __ \/ / / / __ \  #
#   / __  / / / / / / /  |/ /  / / __/ /_/ / / / / / / / /_/ /  #
#  / /_/ / /_/ / /_/ / /|  /  / /_/ / _, _/ /_/ / /_/ / ____/   #
# /_____/\____/\____/_/ |_/   \____/_/ |_|\____/\____/_/        #
#                                                               #
#                                                               #
# Buun Group Pty Ltd.                                           #
# Copyright 2025 Buun Group Pty Ltd. All rights reserved.       #
# https://buungroup.com                                         #
#                                                               #
#################################################################

```

# template-terraform-azure-resources-master

<!-- Brief description of the module -->

## Usage

```hcl
module "template-terraform-azure-resources-master" {
  source = "github.com/BuunGroup-Templates/template-terraform-azure-resources-master?ref=v1.0.0" // Replace with correct source and version

  # Add required variables
}
```

## Testing

This module includes experimental integration tests using `terraform test`.
See the `tests` directory for details and example configurations. Run tests from the module root:
```bash
terraform test
```

## Documentation

This project uses [terraform-docs](https://github.com/terraform-docs/terraform-docs) to automatically generate documentation for inputs and outputs.

To generate documentation locally (requires terraform-docs installation):
```bash
terraform-docs markdown table --output-file README.md --output-mode inject .
```

<!-- BEGIN_TF_DOCS -->
<!-- END_TF_DOCS -->

## Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 