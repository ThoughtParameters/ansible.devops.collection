# thoughtparametersllc DevOps Ansible Collection (`thoughtparametersllc.devops`)

## 📜 Summary and Vision

The **`thoughtparametersllc.devops`** collection is a curated set of Ansible roles, playbooks, and modules designed to automate common DevOps tasks. The primary goal is to provide **reusable, idempotent, and well-tested** automation for provisioning infrastructure, deploying applications, and managing system configurations across various environments. This collection will act as a centralized, version-controlled library to ensure consistency and speed up the automation workflow for our projects.

## 🚀 Getting Started & How to Use

1.  **Prerequisites:** Ensure you have **Ansible 2.10+** installed.

2.  **Installation:**

      * **From Ansible Galaxy:**
        ```bash
        ansible-galaxy collection install thoughtparametersllc.devops
        ```
      * **From this Git Repository (for development):**
        ```bash
        ansible-galaxy collection install git+https://github.com/thoughtparametersllc/ansible.devops.collection.git
        ```

3.  **Usage in a Playbook:**
    To use a role from this collection, refer to it by its **Fully Qualified Collection Name (FQCN)**, which is `thoughtparametersllc.devops.<role_name>`.

    ```yaml
    - hosts: all
      become: true
      tasks:
        - name: Install Prometheus Node Exporter
          ansible.builtin.include_role:
            name: thoughtparametersllc.devops.node_exporter
    ```

## 🧬 Developer Contribution Guide

To maintain code quality and consistency, all contributions must follow these guidelines.

1.  **Branching:** Create a feature branch from `main` for any new role or significant change (e.g., `feature/add-prometheus-role`).
2.  **Variable Naming:** All role variables should be prefixed with the role name to avoid conflicts (e.g., `docker_version` instead of `version`).
3.  **Documentation:** Every new role **must include a `README.md`** explaining its purpose, variables, and an example.
4.  **Testing:** All roles should include basic tests. We will use **Ansible Lint** for static analysis and **Molecule** for integration testing.
5.  **Pull Requests:** Submit a pull request to `main`. The PR description should clearly explain the changes and the problem it solves.

## ✅ Testing Strategy

  * **Linting with `ansible-lint`**:
    We will use `ansible-lint` to catch common errors, stylistic issues, and bad practices. A GitHub Action should be set up to run this on every pull request.

    ```bash
    # Install ansible-lint
    pip install ansible-lint

    # Run from the root of the collection
    ansible-lint
    ```

  * **Integration Testing with `Molecule`**:
    Molecule provides a framework for testing roles across different distributions and scenarios. Each new role should ideally have a Molecule test suite.
