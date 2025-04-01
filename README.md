# Devboxes

This repository contains a collection of [Jetify Devbox](https://www.jetify.com/devbox/) configurations to help Catosplace Engineers set up and manage their development environments efficiently.

## Prerequisites

Before you can run the Devbox shell, ensure you have the following installed:

- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - Version control system to clone this repository.
- [NixOS](https://nixos.org/download.html) - Required for Linux environments.
- [Jetify Devbox CLI](https://www.jetify.com/devbox/docs/installation) - Command-line interface for managing Devbox configurations.
- [WSL](https://docs.microsoft.com/en-us/windows/wsl/install) - Recommended for Windows users to run a Linux environment.

## Getting Started

1. **Clone the repository into a folder called `devboxes`:**
    ```sh
    git clone https://github.com/yourusername/catosplace-devcontainers.git devboxes
    cd devboxes
    ```

2. **Access your development environment:**
    
    Follow the instructions provided by the Devbox shell to access and use your development environment.

### Example: Starting the Engineering-Base Devbox

1. **Navigate to the appropriate directory:**
    ```sh
    cd devboxes/engineering-base
    ```

2. **Run the Devbox shell:**
    ```sh
    devbox shell
    ```

## Using `act` to run GitHub Actions locally

Need to create a `.secrets` file with the GITHUB_TOKEN included

```
GITHUB_TOKEN={YOUR_GITHUB_TOKEN}
```
<!-- 
NOTE: Need to add this documents before making these available

## Contributing

We welcome contributions! Please see our [contributing guidelines](CONTRIBUTING.md) for more details.
-->

## License

This project is licensed under the GNU GPLv3 License. See the [LICENSE.md](LICENSE.md) file for details. 

## Contact

For any questions or support, please open an issue on this repository or contact us at [engineering@catosplace.co.nz](mailto:engineering@catosplace.co.nz).
