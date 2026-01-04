# IaC-on-CouldFormation-using-Former-2
## Steps to copy your existing AWS system configuration to IaC on CloudFormation using Former 2
-	Open an account on Former 2 along with your AWS IAM key pair.
-	Once you get sync and get access to the Former 2 https://former2.com/#section-dashboard
<img width="829" height="298" alt="image" src="https://github.com/user-attachments/assets/fa6f32c8-2453-4b90-af69-bc08bc54aecc" />

-	Select the region where you have your AWS configuration.
-	Hit the Scan button. This action will pull your configuration from AWS to Former 2, and it can be saved to be launched in the future through CloudFormation as IaC.
-	In this case, I saved an S3 Bucket with my Resume on a Static Website. 
 
-	Select the file and hit the Generate button at the top.
  
<img width="975" height="530" alt="image" src="https://github.com/user-attachments/assets/46f8e1f8-176a-40c5-b683-adea297abcfb" />


Select the Import button and make the proper selection

 <img width="732" height="372" alt="image" src="https://github.com/user-attachments/assets/53c4567d-3892-4cd2-a1f4-e6abeaf420e4" />

Save the YAML file to your local computer.

