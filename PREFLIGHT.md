# Pre-Flight Checklist

This document outlines a run-down of tasks when building an ansible role from this template skeleton.

- [ ] Update role description & dependencies in `meta/main.yml`
- [ ] Add installation script to `install.sh`
- [ ] Update `.travis.yml` tests
- [ ] Run [Ansible Lint](https://github.com/willthames/ansible-lint)
- [ ] Run Docker tests `distro=gallium playbook=test.yml ./tests/test.sh`
- [ ] Delete the empty role folders (`files`, `handlers`, `templates`, and/or `vars`)
- [ ] Update `CHANGELOG.md` for initial release
- [ ] Update role **Description** in `README.md`
- [ ] Update role **Installation** in `README.md`
- [ ] Update role **Requirements** in `README.md`
- [ ] Update role **Dependencies** in `README.md`
- [ ] Document any **Role Handlers** in `README.md`
- [ ] Document any **Role Variables** and defaults in `README.md`
- [ ] Update role **Credits** in `README.md`
- [ ] Add role to [Ansible Galaxy](https://galaxy.ansible.com)
- [ ] Check `README.md` that all role names and paths are correct
- [ ] Delete the `PREFLIGHT.md` file
