~ AWS Image Resizing using Lambda & S3

~Project Overview
This project is a serverless image processing system built using AWS.
When an image is uploaded to the source S3 bucket,
it automatically triggers an AWS Lambda function
that resizes the image using the Pillow library and stores it in another S3 bucket.



⚙️ Architecture

S3 (source bckt) → Lambda → S3 (destination bckt)


🔁 Workflow

1. Upload image to **source bckt**
2. Lambda function is triggered automatically
3. Image is resized using Pillow lib
4. Resized image is stored in **destination bckt**


🛠️ Technologies Used

- AWS Lambda
- Amazon S3
- Python
- Pillow Library
- AWS SAM/cloudformation (template.yaml)


💡 Features

✔ Automatic image resizing  
✔ Serverless architecture  
✔ Event-driven processing  
✔ Scalable and efficient  


~ Maintainer

Axl (snowii-byte)
