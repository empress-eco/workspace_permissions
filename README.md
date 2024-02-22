<div align="center">
    <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">
    <h3 align="center">Workspace Permissions: Customized Access for Empowered User Management</h3>
    <p align="center">
    Enhance your system's security and productivity by personalizing workspace access. 
    <br />
    <a href="https://empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/workspace_permissions/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/workspace_permissions/issues">Request Feature</a>
    </p>
</div>

## About The Project

### 📖 Overview
Workspace Permissions empowers system administrators to manage workspace visibility based on user roles, fostering a secure, efficient, and organized working environment. 

### 🌟 Key Features
- Configure workspace visibility based on user roles.
- Use both whitelist and blacklist methods for role-based access control.
- Special handling for "Administrator" user, ensuring unrestricted access.
- Hide section names when no workspaces are available.

This solution is built with Empress/ Empress v13, providing a seamless integration for users of this framework.

## Getting Started

### Prerequisites
You need to have Empress/ Empress v13 installed and running on your system.

### Installation
Follow these steps to install Workspace Permissions on your self-hosted site:

```sh
# Navigate to your Empress-bench directory
cd Empress-bench

# Clone the app from GitHub
git clone https://github.com/empress-eco/workspace_permissions.git

# Replace 'MY_SITE' with your site name and install the app
bench --site MY_SITE install-app workspaceperms

# Execute the seeds to modify Empress/Empress/boot.py
bench execute workspaceperms.seeds.execute

# Restart the bench for the modifications to take effect
bench restart
```

## Usage

1. Go into "Workspace Perms List" via the awesome bar.
2. Add a new `Workspace Perms` document.
3. Select the relevant workspace.
4. Set the permissions ("Visible To Roles" and/or "Hidden to Roles") as per your scenario.

For importing multiple Workspace Perms, consider preparing a xlsx-file and use the "Data Import" feature.

## Contributing
We value your contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgements

### License
This project is under the [MIT License](https://github.com/empress-eco/workspace_permissions/blob/main/LICENSE). Your contributions are also licensed under the MIT License.

### Acknowledgements
Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.