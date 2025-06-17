# setup-tfcmt-action

Set up your GitHub Actions workflow with a specific version of tfcmt.

<!-- actdocs start -->

## Description

This action sets up [tfcmt](https://github.com/suzuki-shunsuke/tfcmt) in your GitHub Actions workflow by:

- Installing a specified version of tfcmt
- Verifying the authenticity and integrity of the downloaded binaries to prevent tampering

The tfcmt simplifies commenting on the results of Terraform CLI commands in pull requests.

## Usage

```yaml
  steps:
    - name: Setup tfcmt
      uses: tmknom/setup-tfcmt-action@v0
      with:
        tfcmt-version: 4.14.0
```

## Inputs

| Name | Description | Default | Required |
| :--- | :---------- | :------ | :------: |
| tfcmt-version | The version of tfcmt to install. | `latest` | no |

## Outputs

N/A

<!-- actdocs end -->

## Permissions

N/A

## FAQ

N/A

## Related projects

N/A

## Release notes

See [GitHub Releases][releases].

[releases]: https://github.com/tmknom/setup-tfcmt-action/releases
