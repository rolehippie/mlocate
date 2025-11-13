# mlocate

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/mlocate)
[![General Workflow](https://github.com/rolehippie/mlocate/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/mlocate/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/mlocate/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/mlocate/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/mlocate/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/mlocate/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/mlocate)](https://github.com/rolehippie/mlocate/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.mlocate-blue)](https://galaxy.ansible.com/rolehippie/mlocate)

Ansible role to simply drop mlocate.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of contents

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [mlocate_state](#mlocate_state)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### mlocate_state

State for the mlocate package

#### Default value

```YAML
mlocate_state: absent
```

## Discovered Tags

**_mlocate_**

## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
