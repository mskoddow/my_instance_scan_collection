# My Instance Scan Collection

## Overview

This repository contains a custom application for ServiceNow called **My Instance Scan Collection**. This application contains several hundred hand-picked and completely new instance scan checks that I have collected over the past few years. The primary focus of these checks is on basic platform and security issues, making them ideal for hardening ServiceNow instances. They cover a wide range of areas, including but not limited to:

- **Platform Security**: Checks to ensure that the platform is configured securely.
- **Data Integrity**: Checks to ensure that the data within the platform is consistent and reliable.
- **Performance Optimization**: Checks to identify and rectify performance bottlenecks.
- **Compliance**: Checks to ensure that the platform adheres to relevant compliance standards.

## Additional Functionalities

In addition to the instance scan checks, this application provides several extra functionalities to enhance the ServiceNow platform. These functionalities include:

- **Application Menu**: You can find everything in the "All" menu below the application "My Instance Scan Collection"
- **Predefined Instance Scan Suites**: All checks are assigned to one of the three topic-based scan suites that are bundled under the "[My Instance Scan Collection] Main" scan suite.


## Installation

To install this application, follow these steps:

1. Fork the repository using the instructions provided at https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo.

   Tip: A clone is generally not required because tools like the ServiceNow Studio can connect to and work with remote repositories.
2. Link and import the forked repository into ServiceNow by following the instructions in the great article at https://jessems.com/posts/2024-03-21-linking-a-servicenow-app-in-studio-to-a-github-repository.

## Usage

Once the application is imported into your ServiceNow instance, you can access the instance scan checks and prebuilt scan suites through the ServiceNow interface. Detailed usage instructions are available in the ServiceNow documentation pages at https://www.servicenow.com/docs/csh?topicname=hs-using-scans.html&version=latest.

## Troubleshooting

If you encounter any issues with the application, you can ...

## Contributing

I welcome contributions to improve this application and extend the collection with even more instance scan checks. To contribute, please create pull requests and I will review them.

## License

This project is licensed under the "GNU General Public License v3.0". See the LICENSE file for more details.
