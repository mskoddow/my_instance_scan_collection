# My Instance Scan Collection

## Overview

This repository contains a custom application for ServiceNow called **My Instance Scan Collection**. This application contains several hundred hand-picked and completely new instance scan checks that I have collected over the past few years. The primary focus of these checks is on basic platform and security issues, making them ideal for hardening ServiceNow instances. They cover a wide range of areas, including but not limited to:

- **Platform Security**: Checks to ensure that the platform is configured securely.
- **Data Integrity**: Checks to ensure that the data within the platform is consistent and reliable.
- **Implementation**: Checks to identify deviations from the development recommendations.
- **Compliance**: Checks to ensure that the platform adheres to relevant compliance standards.

## Additional Functionalities

In addition to the instance scan checks, this application provides several extra functionalities to enhance the ServiceNow platform. These functionalities include:

- **Application Menu**: You can find everything in the "All" menu below the application "My Instance Scan Collection"
- **Predefined Instance Scan Suites**: All checks are assigned to one of the three topic-based scan suites that are bundled under the "[My Instance Scan Collection] Main" scan suite.


## Installation

To install this application, follow these steps:

1. Fork the repository using the instructions provided [in the GitHub documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).

   Tip: A clone is generally not required because tools like the ServiceNow Studio can connect to and work with remote repositories.
2. Link and import the forked repository into ServiceNow by following the instructions in [a great article by Jesse](https://jessems.com/posts/2024-03-21-linking-a-servicenow-app-in-studio-to-a-github-repository).

   Hint: As the new ServiceNow Studio still has no Git capabilities you have to do perform all Git-based activities in the legacy Studio.

## Usage

Once the application is imported into your ServiceNow instance, you can access the instance scan checks and prebuilt scan suites through the ServiceNow interface. Detailed usage instructions are available [in the ServiceNow documentation pages](https://www.servicenow.com/docs/csh?topicname=hs-using-scans.html&version=latest).

Each check can be used individually or transferred to other applications or suites, as there are no central or external dependencies, such as script includes.

In order to deactivate checks without touching them, I have built a condition into all checks which verifies whether a value exists for an related system property (consisting of table name and Sys ID). If yes, the condition returns “false” and the check is not executed.

## Troubleshooting

If you encounter any issues with the application, you can [create an issue](https://github.com/mskoddow/my_instance_scan_collection/issues)

## Contributing

I welcome contributions to improve this application and extend the collection with even more instance scan checks. To contribute, please create pull requests and I will review them.

## License

This project is licensed under the "GNU General Public License v3.0". See the [LICENSE file](https://github.com/mskoddow/my_instance_scan_collection/blob/master/LICENSE) for more details.
