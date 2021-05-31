# install-epel-release-repository

This role enables to install epel-release on the target machines.

## Requirements

No requirements.

## Role Variables

| Name                       | Type   | Location            | Description                                                                                                                                                        |
| -------------------------- | ------ | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| epel_release_7_rpm_url     | string | `defaults/main.yml` | URL of the RPM to install to add epel-release repositories for RHEL7 system. Defaults to `https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm`. |
| epel_release_7_gpg_key_url | string | `defaults/main.yml` | URL of the GPG key to import to be able to install RPM from URL. Only for RHEL7 system. Defaults to `https://dl.fedoraproject.org/pub/epel/RPM-GPG-KEY-EPEL-7`.    |
| epel_release_8_rpm_url     | string | `defaults/main.yml` | URL of the RPM to install to add epel-release repositories for RHEL8 system. Defaults to `https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm`. |
| epel_release_8_gpg_key_url | string | `defaults/main.yml` | URL of the GPG key to import to be able to install RPM from URL. Only for RHEL8 system. Defaults to `https://dl.fedoraproject.org/pub/epel/RPM-GPG-KEY-EPEL-8`.    |

## Dependencies

No dependencies.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: julb.install_epel_release_repository }
```

## License

MIT

## Author Information

More to find on my [Github](https://github.com/julb).

## Contributing

This project is totally open source and contributors are welcome.

When you submit a PR, please ensure that the syntax has been checked.
