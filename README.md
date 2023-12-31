Mass Password Changer


Overview

This project is a collection of Ansible scripts designed to enhance network security by automating user account management and SSH key handling. It's ideal for administrators looking to streamline network host security.

# This assumes you're not using LDAP; using this against LDAP-bound servers may result in unintended consequences.

Features

- User Account Listing: List all user accounts across network hosts.
- Password Reset: Automate the process of setting random temporary passwords for non-system users.
- SSH Key Management: Replace authorized_keys files with the admin's public SSH key to ensure secure access.

