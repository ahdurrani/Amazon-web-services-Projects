# Project Title

Low-Cost AWS Solution for Seamless Application Deployment and Data Management

## Project Overview

This project aims to provide a low-cost AWS solution to address the challenge of seamless application deployment and efficient data management. By leveraging various AWS services such as EC2, ELB, Route 53, RDS PostgreSQL, and S3 object storage, we have designed a scalable and resilient infrastructure setup.

## Key Features

- Deploy EC2 instances in two Availability Zones (AZs) for high availability and fault tolerance.
- Utilize ELB Application Load Balancer connected with Route 53 for seamless traffic distribution and DNS management.
- Automatic scaling of EC2 instances during peak times to handle high request loads without downtime.
- Fast application deployment using Code Pipeline for efficient continuous integration and delivery.
- Implement Multi-AZ deployment for RDS PostgreSQL to ensure data durability and facilitate disaster recovery.
- Safeguard data with S3, a cost-effective and durable object storage solution.

## Architecture Diagram

![High-Level Architecture](https://cdn.theforage.com/vinternships/companyassets/pmnMSL4QiQ9JCgE3W/4MmBKDutGPxKkaRq4/1638534392235/Architecture%20Diagram.png)

The above diagram illustrates the high-level architecture of the deployed solution. It showcases the interaction between EC2 instances, ELB, Route 53, RDS PostgreSQL, and S3 Object storage for backup.

## Setup Instructions

1. Clone this repository: `git clone https://github.com/your-username/your-repo.git`
2. Follow the detailed setup instructions in the [Installation Guide](installation-guide.md) to provision the required AWS resources and configure the infrastructure.
3. Customize the configurations and settings as per your application requirements.
4. Deploy your application using the provided Code Pipeline setup and monitor the process.

## Usage

1. Modify the application code in the `src` directory to match your specific requirements.
2. Commit and push the changes to the repository.
3. Code Pipeline will automatically detect the changes and trigger the deployment process.
4. Monitor the deployment pipeline and verify the successful deployment of your application.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to express our gratitude to the AWS team for providing excellent documentation and resources on their services, which greatly facilitated the development of this project.

## Contact

For any inquiries or further information, please contact [your-email@example.com](mailto:your-email@example.com).
