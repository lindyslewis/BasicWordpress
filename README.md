# BasicWordpress

CloudFormation template that launches a preconfigured AMI 


# deploy.sh

 - calls aws cloudformation create-stack
 - passes in the CloudFormation template JSON file

# wordpress_cloud_formation_template.json

 - LaunchConfig uses preconfigured ami
 - ASG of size 1

  
  
# preconfigured ami includes

- Wordpress
- Divi
- Plugins
