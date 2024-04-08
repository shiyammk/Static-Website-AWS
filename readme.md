**Procedure to Host a Static Web Page in AWS**

**Create an S3 Bucket for file upload like index.html**

![st2](https://github.com/shiyammk/Static-Website-AWS/assets/160907011/74cdd06a-0983-4471-920c-575c4eaa2705)

**Create an EC2 Instance and attach IAM Role created for S3 access**

![st1](https://github.com/shiyammk/Static-Website-AWS/assets/160907011/3f44b91d-72ce-447d-9a39-153c001a1959)

**Create an IAM Role for S3**

![st2](https://github.com/shiyammk/Static-Website-AWS/assets/160907011/6c7de2b4-e503-40d4-833f-0f79b53cefbd)

**Add user data while creating an EC2 Instance**

#! /bin/bash

sudo yum-y update

sudo yum-y install httpd

sudo systemctl start httpd

sudo systemctl enable httpd

**connect instance with SSH or Web Here is the command to copy the file from S3 bucket to host a static web page**

![st5](https://github.com/shiyammk/Static-Website-AWS/assets/160907011/fb512b47-63e2-46d1-bd59-edaa28c10f53)

**The final output for Static website**

![st6](https://github.com/shiyammk/Static-Website-AWS/assets/160907011/493fc2f2-e326-45f9-a04f-7665984d8a1d)
