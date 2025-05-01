🔐 SSH Key (keyssh) for Ansible Automation
This repository provides the keyssh private SSH key used by Ansible to enable secure, automated access to remote systems or private repositories during provisioning and deployment tasks.

✅ Purpose of keyssh
In Ansible, many operations — like cloning a private Git repo or connecting to remote servers — require secure SSH authentication.

The keyssh file is used to:

Authenticate with remote hosts over SSH (instead of using passwords).

Access private Git repositories when using the git module.

Enable automation without interactive logins (essential for CI/CD).

