<h1 align="center"> AWS Cloud </h1>

# S3 (Simple Service Storage)

- Search Bar -> S3 -> Buckets -> Create bucket

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/6748cdbc-7f99-4cc3-9759-e5df4aa588b9)

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/29108645-6626-4a36-9361-35a3fe03e157)

Rest keep everything as by default and create a Bucket.

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/8de25362-a3aa-41c1-bcfb-3d8cb0dd23fd)

Successfully, we have created a bucket.

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/7675c099-9beb-41c5-813d-e772862c0425)

Here, we can uploads objects (for eg:- images,files,etc) in this bucket.

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/20e1c610-d09b-4fe3-b32d-38eb4c65026a)

Above we have upload an image as an object in this bucket.

Now, we want that this image should be public accessible so for that we need to give public access by unchecking the 
block all public access

bucket -> permission -> block public access

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/3f17c237-565f-49ad-a40b-2eec5c23c0fc)

Now below this there is a Generate Policy so generate it and paste it in Edit Bucket Policy.

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/f28875e1-0417-4d24-8728-740209059fda)

Action is GetObject -> click on Add Statement -> Generate Policy

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/e5b67f2e-49dc-4876-ac61-d684e490740b)

Now, paste the above content below

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/e7c87999-5633-45cf-8e03-9f0a7ae068da)

**Successful that object is publicly accessible.**

## Versioning

Select the created Bucket -> Properities -> Edit Bucket Versioning

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/b113541a-1572-4b69-b5dc-8a49a551a9a8)

After save changes you will get the option of show versions

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/114cc43d-4d1d-45be-a357-35e015bc058e)

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/d545988b-f42a-4687-87ae-c4f2c9a0fff5)

We have uploaded another image with the same name so as we have enabled the versioning property so we can now see both the results.

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/2210ee38-7a94-4f0b-8af2-4245e0aff7cf)

 **How to create a billing alarm in AWS**
 
- search bar -> Cloudwatch -> Alarms -> billing -> create Alarm

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/0165a618-4763-4372-8798-243013f405e3)

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/80fb028d-4109-4d40-a330-c311ac63b252)

Next button -> Give Name for this Alert and it's Description -> Next -> Create Alarm -> From Email click on confirm subscription -> refresh Page -> Done

<h3 align="center"> Static Website hosting in S3 </h3>

Create a bucket -> Upload necessary files -> Refresh -> Properties -> Scroll Down & click on Edit Static Website Hosting -> Enabled

![image](https://github.com/Pramanik4/AWS_Cloud/assets/75212387/51e83c9f-5b1d-42f0-8b19-5454464b95e2)

You will get Error So to resolve this...You have to follow the same process of Generate Policy.

