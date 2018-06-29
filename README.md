# Remi Repo Ansible Role

This role provides support for Remi's RPM repository.

## Requirements

* Ansible 2.4+

## Dependencies

* rchouinard.repo-epel (for Enterprise Linux)

## Example Playbook

``` yaml
- hosts: localhost
  roles:
    - rchouinard.repo-remi
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
