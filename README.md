# Cloudformation template . 

This template Creates vpc , subnet and security groups . Launches instance with httpd installed

- Clone the repo

$git clone https://github.com/alviahsan/cfn.git

- Assuming you have aws cli setup 

$aws cloudformation create-stack --stack-name testStack --template-body .cfn/cfn.template


- Using Eclipse which is already setup with aws eclipse toolkint

Drag and drop the template to eclipse into your project it will recognize the template as cloudformation template
