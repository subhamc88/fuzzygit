# FuzzyGit

FuzzyGit is a command-line tool that enhances Git workflows by
integrating fuzzy search capabilities.
It combines the features of Fugitive.nvim and Telescope.nvim while being usable
outside of Neovim, offering a seamless experience for developers.

## Features

- **Fuzzy Searching**: Quickly find branches, commits, and pull requests with intuitive
search functionality.
- **Easy Configuration**: Customize your experience using TOML configuration files.
- **User-Friendly Interface**: Built with Cobra for a clean command-line interface.
- **Lightweight**: Minimal resource usage without compromising on features.

## Installation

To install FuzzyGit, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/subhamc88/fuzzygit.git
   cd fuzzygit
   ```

2. **Build the Application**

   ```bash
   go build
   ```

3. **Move the Binary to Your PATH**

   ```bash
   mv fuzzygit /usr/local/bin/
   ```

4. **Verify the Installation**

   ```bash
   fuzzygit --help
   ```

## Usage

FuzzyGit provides various commands to streamline your Git operations. Access the
help documentation with:

```bash
fuzzygit --help
```

### Common Commands

- **List Branches**

  ```bash
  fuzzygit branches
  ```

- **Search Commits**

  ```bash
  fuzzygit commits
  ```

- **Find Pull Requests**

  ```bash
  fuzzygit prs
  ```

## Configuration

FuzzyGit utilizes a TOML configuration file for customization.
By default, it searches for a file named `fuzzygit.toml` in the `~/.config` directory.
You can specify a different configuration file using the `--config` flag:

```bash
fuzzygit --config /path/to/your/config.toml
```

## Contributing

We welcome contributions!
Please review our [Contributing Guidelines](CONTRIBUTING.md) for more information
on how to contribute.

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md).
Please read it to understand our expectations for participants.

## License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the contributors who enhance this project.
- Inspired by tools like Fugitive.nvim and Telescope.nvim.

## Contact

For inquiries or feedback, reach out at [subham020304@gmail.com](mailto:subham020304@gmail.com).
