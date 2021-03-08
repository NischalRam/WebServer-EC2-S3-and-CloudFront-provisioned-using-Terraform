# WebServer — EC2, S3 and CloudFront provisioned using Terraform

<b>Write an Terraform code that does the following operations</b>
<ul>
  <li>Create the key and security group which allows the ports.
like
    <ul style="list-style-type:circle">
 <li> a.shh port : 22</li>
  <li>b.http port:80</li>
      </ul>
      </li>
  <li>Launch EC2 instance</li>
  <li> in the EC2 instance use the key and security group which we have created in step 1</li>
  <li>Launch one Volume (EBS) and mount that volume into /var/www/html</li>
  <li>import the code which is uploaded by the developer from GitHub Repositories</li>
  <li>import the code which is uploaded by the developer from GitHub Repositories</li>
  <li>Create an S3 bucket, and deploy the images from GitHub Repositories or from the local file into the S3 bucket and change the permission to public readable. (so that everyone can access )</li>
  <li>Create a Cloudfront using S3 bucket(which contains images) and use the Cloudfront URL to update in code in /var/www/html</li>
</ul>

everything is expected here 🔗
 <a href= "https://nischalvooda.medium.com/webserver-ec2-s3-and-cloudfront-provisioned-using-terraform-github-40b659e99ae6" target="_blank">Blog</a>
