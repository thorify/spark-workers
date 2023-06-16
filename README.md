# Spark Workers for Personal Lakehouse

This repository provides the configuration for adding additional Spark Workers to your Personal Lakehouse setup. By deploying these Spark Worker instances on separate machines, you can significantly boost the computational power of your Spark cluster.

## Prerequisites
Before getting started, make sure you have the following:

- Docker installed on the machines where you want to deploy the additional Spark Workers.
- A running Spark cluster with Spark Master already set up as in [The Lakehouse Procject](https://github.com/thorify/lakehouse)

## Getting Started
To add the additional Spark Workers to your Personal Lakehouse, follow these steps:

1. Clone this repository to your local machine.
2. Modify the `docker-compose.yml` file with the appropriate configurations, such as the Spark Master URL and resource allocation for each Spark Worker.
3. Deploy the additional Spark Workers by running the command `docker-compose up -d`.

## Contributing
Contributions to this repository are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
If you have any questions or need further assistance, please feel free to reach out.
