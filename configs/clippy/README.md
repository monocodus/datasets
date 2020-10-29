# Clippy configs

This dataset contains Clippy configuration files `.clippy`, `.clippy.toml` parsed from open-source repositories on GitHub.
Empty and misformatted files were omitted. Only valid files presented.

The data is stored in the `JSON` format. Each object represents a single config file in the repository.

Each object has following fields
 - `repo_name` - name of repository on GitHub
 - `repo_url` - URL of repository on GitHub
 - `config_path` - path to config file in the repository
 - `config_text` - text of config file

The information provided was current at the time it was collected. Over time, the current state of affairs may have changed.