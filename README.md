[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=jlvcm&repository=ha-actualbudget)

:star: If you appreciate this integration, please consider giving it a star! Your support encourages me to continue improving and expanding this project. Thank you! :star:

# Actual Budget integration for Home Assistant

This is a custom integration for Home Assistant that allows you to track your actual budget.

Note: It's a work in progress, it should work but it may have some bugs and breaking changes.

# Features

- Gets all accounts balance and set it as sensors
- Gets all budgets and set the current month as sensors (last month and total are set as extra attributes)

# Installation

## HACS

1. Go to HACS page
2. Search for `Actual Budget`
3. Install it

Note: If this is not in HACS yet, you can add this repository manually.

# Configuration

1. Go to Configuration -> Integrations
2. Click on the "+" button
3. Search for `Actual Budget`
4. Enter the needed information

| Setting       | Required | Description |
| ------------- | --------- | ----------- |
| Endpoint      | Yes       | The endpoint of the Actual Budget API |
| Password      | Yes       | The password of the Actual Budget API |
| Encrypt Password | No    | The password to decrypt the Actual Budget file (if set) |
| File          | Yes       | The file id of the Actual Budget file |
| Cert          | No        | The certificate to use for the connection |
| Currency      | Yes        | |

Example:

```
Endpoint: https://localhost:5001
Password: password
Encrypt Password: ''
File: ab7c8d8e-048b-41b1-a9cf-13f0679edc0b
Cert: 'SKIP'
```
