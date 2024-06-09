# Container Based Next.js Website with AWS Deployment

This project is a simple practice while learning AWS as an AWS Solutions Architect Associate. It involves integrating a Next.js website and deploying it to an AWS EC2 instance.

## Project Overview
![image](https://github.com/chunghei0116/ec2-web-container/blob/main/public/container-based-web.drawio.png)

The project includes the following components:

1. **Next.js**: The website is built using the Next.js framework, which provides server-side rendering and other features.
2. **AWS EC2**: The website is deployed to an AWS EC2 instance, which will host the application.
3. **Security Group**: A security group is configured to allow necessary traffic to the EC2 instance.
4. **IAM**: IAM (Identity and Access Management) is used to manage the permissions and access to the AWS resources.

## Getting Started

1. Clone the GitHub repository: `git clone https://github.com/your-username/your-repo.git`
2. Install the dependencies: `npm install`
3. Build the Next.js application: `npm run build`
4. Start the development server: `npm start`

## Deployment to AWS

1. Create an AWS EC2 instance.
2. Configure the security group to allow necessary traffic (e.g., HTTP, HTTPS).
3. Deploy the Next.js application to the EC2 instance.
4. Set up any necessary IAM roles and permissions for the deployment.

For detailed instructions on the deployment process, please refer to the AWS documentation or consult with an AWS Solutions Architect.

## License

This project is licensed under the [MIT License](LICENSE).
