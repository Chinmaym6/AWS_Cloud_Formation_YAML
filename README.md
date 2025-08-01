# AWS_Cloud_Formation_YAML
This is a Repo for (YAML) code for AWS Infrastructure Creation Throught CLoud_Frmation_Template (Iac)

## Features
- **Infrastructure as Code**: Define your AWS infrastructure using YAML templates.
- **Reusable Templates**: Easily modify and reuse templates for different environments or projects.
- **Version Control**: Track changes to your infrastructure code using Git.
- **Automation**: Automate the deployment of AWS resources with CloudFormation.

## How to use the Codes :-
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Chinmaym6/AWS_Cloud_Formation_YAML.git
    ```
2. Navigate to the directory containing the CloudFormation templates:
    ```bash
    cd AWS_Cloud_Formation_YAML
    ```
3. Open the desired YAML file in your preferred text editor or IDE.
4. Modify the parameters as needed for your AWS environment.
5. Deploy the CloudFormation stack using the AWS CLI or AWS Management Console:

    - **Using AWS CLI**:
        1. Ensure you have the AWS CLI installed and configured with your credentials.
        2. Use the following command to create a stack from your YAML template:
        
        ```bash
        aws cloudformation create-stack --stack-name <your-stack-name> --template-body file://<path-to-your-template>.yaml
        ```
        
        Replace `<your-stack-name>` with a name for your stack and `<path-to-your-template>` with the path to your YAML file.

    - **Using AWS Management Console**:
        #Steps:
            1. Go to AWS Management Console 
            2. Navigate to CloudFormation
            3. Click on "Create Stack" and choose "With new resources (standard)"
            4. Choose "Upload a template file" or "Specify an Amazon S3 template URL" or Sync to GitHub
            5. Upload your YAML file and click next 
            6. Enter the stack name and parameters
            7. Review the settings and click "Create stack"
            8. Wait for the stack creation to complete.
            9. And verify by checking if each service is created
            10. You can also check the status of your stack in the CloudFormation console.
    

## Contributing
If you would like to contribute to this repository, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add your commit message here"
    ```
4. Push your changes to your fork:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Create a pull request to the main repository.
