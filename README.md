# IaC-on-CouldFormation-using-Former-2
## Steps to copy your existing AWS system configuration to IaC on CloudFormation using Former 2
-	Open an account on Former 2 along with your AWS IAM key pair.
-	Once you get sync and get access to the Former 2 https://former2.com/#section-dashboard
<img width="829" height="298" alt="image" src="https://github.com/user-attachments/assets/fa6f32c8-2453-4b90-af69-bc08bc54aecc" />

-vSelect the AWS region where your resources are currently configured.

- Click the Scan button. This will retrieve your existing AWS configuration and load it into Former2, allowing it to be saved and reused later as Infrastructure as Code (IaC) through CloudFormation.

- In this example, an S3 bucket hosting a static resume website was scanned and saved.

- Finally, select the generated file and click the Generate button at the top to produce the CloudFormation template.
  
<img width="975" height="530" alt="image" src="https://github.com/user-attachments/assets/46f8e1f8-176a-40c5-b683-adea297abcfb" />


Select the Import button and make the proper selection

 <img width="732" height="372" alt="image" src="https://github.com/user-attachments/assets/53c4567d-3892-4cd2-a1f4-e6abeaf420e4" />

Save the YAML file to your local computer.

