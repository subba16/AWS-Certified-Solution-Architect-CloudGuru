### AWS CERTIFIED SOLUTION ARCHITECT MATERIALS

<details>
<summary>Exams and their levels</summary>
Schemes:

![tiers](readme-images/tiers.png)
![difficult](readme-images/difficulty.png)
![major-themes](readme-images/major-themes-before-exam.png)

</details>

<details>
<summary>Section 1: Basis</summary>
Schemes:

![basis](readme-images/AWS-Basis-AvailabilityZone.png)
![basis](readme-images/AWS-Basis-AvailabilityZone2.png)
![basis](readme-images/AWS-Basis-Region.png)
![basis](readme-images/AWS-Basis-Edge-Location.png)
![basis](readme-images/AWS-Basis-Web-Application-Firewall-WAF.png)
![basis](readme-images/AWS-Basis-Snowball.png)
![basis](readme-images/AWS-Basis-Snowball-edge-portable-AWS.png)

</details>

<details>
<summary>Section3: IAM</summary>

![IAM-info1](readme-images/section3-IAM-101-Pic1.png)
![IAM-info2](readme-images/section3-IAM-101-Pic2.png)
</details>

<details>
<summary>Section3: S3 Storage Information</summary>

![S3-1](readme-images/S3-storage-classes.png)
![S3-2](readme-images/S3-Glacier(to%20Archive%20the%20data).png)
![S3-3](readme-images/S3-consistency.png)
![S3-4](readme-images/S3-Objects-consist-of.png)
![S3-exam-1-1](readme-images/S3-Storages-Availability.png)
![S3-exam-1-2](readme-images/S3-minimum-file-size.png)
</details>

<details>
<summary>Section3: S3 Encryption</summary>

![S3-5](readme-images/S3-bucket-policies(ACL,Bucket%20Policies).png)
![S3-5](readme-images/S3-encryption--transit,rest(Server-side),client.png)

</details>

<details>
<summary>Section3: S3 Versioning</summary>

![S3-versioning-1](readme-images/S3-versioning1.png)

</details>

<details>
<summary>Section3: S3 Lifecycle management</summary>

You could move your data between storage types: From Standard to Glacier, for example.
![S3-lifecycle-management](readme-images/S3-Lifecycle-Management.png)

</details>

<details>
<summary>Section3: S3 Cross-Region Replication</summary>

[AWS Replication Info](https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html)

Replication enables automatic, asynchronous copying of objects across Amazon S3 buckets. 

Buckets that are configured for object replication can be owned by the same AWS account or by different accounts. 
You can copy objects between different AWS Regions or within the same Region.

![S3-replication](readme-images/S3-replication.png)


</details>

<details>
<summary>Section3: S3 Transfer Acceleration</summary>

![S3-transfer-acceleration](readme-images/S3-Transfer-Acceleration.png)
![S3-transfer-acceleration](readme-images/S3-Transfer-Acceleration-edge-locations-scheme.png)
![S3-transfer-acceleration](readme-images/S3-Transfer-Acceleration-test-tool.png)

</details>

<details>
<summary>Section3: CloudFront</summary>

![CloudFront](readme-images/CloudFront-Key-Terminology.png)
![CloudFront](readme-images/CloudFront-Basis.png)
![CloudFront](readme-images/CloudFront-Cached-Resources.png)
![CloudFront](readme-images/CloudFront-EdgeLocations-Updating-Files.png)
Invalidating Files:
If you need to remove a file from CloudFront edge caches before it expires, you can do one of the following:
Invalidate the file from edge caches. The next time a viewer requests the file, CloudFront returns to the origin to fetch the latest version of the file.
Use file versioning to serve a different version of the file that has a different name. For more information, see Updating Existing Files Using Versioned File Names.

Important:
You cannot invalidate objects that are served by an RTMP distribution.
To invalidate files, you can specify either the path for individual files or a path that ends with the * wildcard, which might apply to one file or to many, as shown in the following examples:
/images/image1.jpg

/images/image*

/images/*
![CloudFront](readme-images/CloudFront-Distribution-Invalidations.png)

</details>

<details>
<summary>Section3: Snowball</summary>

![Snowball](readme-images/AWS-Basis-Snowball.png)
![Snowball](readme-images/AWS-Basis-Snowball2.png)
![Snowball](readme-images/Snowmobile.png)
![Snowball](readme-images/AWS-Basis-Snowball-edge-portable-AWS.png)
![Snowball](readme-images/AWS-Basis-Snowball-edge2-portable-AWS.png)

</details>

<details>
<summary>Section3: Storage Gateway - Basis</summary>

![Gateway](readme-images/Storage-gateway.png)
![Gateway](readme-images/Storage-gateway2.png)
![Gateway](readme-images/Storage-gateway3.png)
![Gateway](readme-images/Storage-gateway-types.png)
![Gateway](readme-images/Volume-gateway.png)
![Gateway](readme-images/Gateways-types-exam-tips.png)

</details>

<details>
<summary>Section3: File Gateway</summary>

![Gateway](readme-images/File-gateway.png)
![Gateway](readme-images/File-gateway2.png)

</details>

<details>
<summary>Section3: Volume Gateways</summary>

![Gateway](readme-images/Volume-gateway.png)
Stored Volumes:
![Gateway](readme-images/Volume-gateway-stored-volumes.png)
![Gateway](readme-images/Volume-gateway-stored-volumes-scheme.png)
Cached Volumes:
![Gateway](readme-images/Volume-gateway-cached-volume.png)
![Gateway](readme-images/Volume-gateway-cached-volume-scheme.png)
Tape Gateway:
![Gateway](readme-images/Volume-gateway-Tape-gateway.png)
![Gateway](readme-images/Volume-gateway-Tape-gateway-scheme.png)

</details>

<details>
<summary>Section3: S3 Exam tips</summary>

![S3-exam-1](readme-images/S3-exam-tips.png)
![S3-exam-1-1](readme-images/S3-Storages-Availability.png)
![S3-exam-1-2](readme-images/S3-minimum-file-size.png)
![S3-exam-2](readme-images/S3-exam-tips2.png)
![S3-exam-3](readme-images/S3-exam-tips3.png)
![S3-exam-4](readme-images/S3-exam-tips4.png)
![S3-exam-5](readme-images/S3-exam-tips5.png)
![S3-exam-6](readme-images/S3-versioning2.png)
![S3-exam-7](readme-images/S3-Lifecycle-Management.png)
![S3-exam-8](readme-images/S3-replication.png)
![S3-exam-9](readme-images/S3-Transfer-Acceleration.png)
![S3-exam-10](readme-images/CloudFront-Cached-Resources.png)
![S3-exam-11](readme-images/CloudFront-EdgeLocations-Updating-Files.png)
![S3-exam-12](readme-images/Gateways-types-exam-tips.png)
* SAML: [Security Assertion Markup Language 2.0](https://aws.amazon.com/identity/saml/) -  
is an open standard for exchanging identity and security information with applications and service providers.
</details>


<details>
<summary>Section4: EC2 Basis</summary>

![EC2-Basis](readme-images/EC2-Description.png)
![EC2-Basis](readme-images/EC2-types.png)
![EC2-Basis](readme-images/EC2-types-mnemonic-first-char.png)
![EC2-Basis](readme-images/EC2-pricing.png)
![EC2-Basis](readme-images/EC2-pricing2.png)
![EC2-Basis](readme-images/EC2-pricing3.png)
![EC2-Basis](readme-images/EC2-pricing4.png)
![EC2-Basis](readme-images/EC2-pricing5.png)
![EC2-Basis](readme-images/EC2-pricing6.png)
![EC2-Basis](readme-images/EC2-Spot-instance-termination.png)
</details>

<details>
<summary>Section4: Lab1-tips</summary>

To create SSH public key for EC2 you need to run next command in command line:
ssh-keygen -y -f Glareone-EC2-Lab1-Key-Pair.pem > MyKP.pub
"Glareone-EC2-Lab1-Key-Pair.pem" - key pair file from console.

* To resolve problem with permissions on this key:
[windows-ssh-permissions-for-private-key](https://superuser.com/questions/1296024/windows-ssh-permissions-for-private-key-are-too-open)

To run SSH commands you could use "Secure Shell App" Chrome extension.
to come into your machine you have to use its ip-address (IPv4 Public IP in Instances: [EC2-instances](https://console.aws.amazon.com/ec2/home?region=us-east-1#Instances:sort=instanceId))
* our: 54.84.6.245
* user - ec2-user

on machine: 
* yum update -y (update all packages on your machine)
* yum install httpd -y (install httpd)

[root@ip-172-31-82-192 html]# cd var/www/html
[root@ip-172-31-82-192 html]# nano index.html (create index.html in nano, just create a very simple html doc)
[root@ip-172-31-82-192 html]# service httpd start (start httpd server)
[root@ip-172-31-82-192 html]# chkconfig on (rerun httpd server if our server rebooted accidentally)

check how it works: just copy address to your browser.

</details>



<details>
<summary>Section4: EC2 Exam tips</summary>

![EC2-exam1](readme-images/EC2-Description.png)
![EC2-exam2](readme-images/EC2-types.png)
![EC2-exam3](readme-images/EC2-Spot-instance-termination.png)
![EC2-exam4](readme-images/EC2-Spot-instance-termination.png)
</details>