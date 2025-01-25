# TD2551-4G
Education Anti Spam

This repository contains a GitHub Actions workflow to automatically install Tailscale on a Windows Server 2022 environment, and configure the server with some additional settings.

## Features
- Installs Chocolatey package manager
- Installs Tailscale via Chocolatey
- Starts the Tailscale service
- Configures the server for Remote Desktop access

## License

This project is licensed under the MIT License. By using this software, you agree to the following terms:

1. **Chống Lạm Dụng Tài Nguyên**: Do not misuse GitHub's Actions resources. This project is intended for educational or experimental use. Excessive use, particularly for tasks that do not comply with GitHub's terms of service, may result in account suspensions or bans.
2. **Use for Experimentation Only**: This is a trial or experimental project. Please refrain from running this workflow for production or high-volume tasks.
3. **GitHub Account Risk**: Any violation of GitHub's usage guidelines, especially concerning abusive usage or overutilization of resources, can result in suspension or termination of your GitHub account.

## How to Use

1. **Fork or Clone the Repository**: Fork this repository to your GitHub account, or clone it to your local machine.
2. **Update Workflow**: Customize the workflow if needed (e.g., modify user settings or server configurations).
3. **Push to GitHub**: Push changes to the `main` branch, and the GitHub Actions workflow will automatically run.
4. **Monitor Usage**: Be mindful of your resource usage to avoid violating GitHub's terms of service. Ensure that the workflow is used for testing and learning purposes only.

## Requirements

- GitHub account with Actions permissions enabled
- A Windows Server 2022 environment on the GitHub runner (provided by `runs-on: windows-2022`)

## Notes

- This project is intended for trial purposes. Do not use it for large-scale or continuous tasks that could lead to an abuse of GitHub's resources.
- If you notice unusual behavior or errors in the workflow, it is important to review GitHub's usage policies to avoid potential issues with your account.

## License

This project is licensed under the [MIT License](LICENSE).
