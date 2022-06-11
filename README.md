<h1>Deploy Static Website on AWS</h1>

Screenshots showing steps for Deploying Static Website on AWS.

The following activities has been performed:

<ol>
  <li>All website files are added to the S3 bucket.</li>
  <li>The bucket configuration is set up to support static website hosting.</li>
  <li>The S3 bucket is configured to support static website hosting.</li>
  <li>The permission access to the bucket is configured to allow public access.</li>
  <li>The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.</li>
</ol>


Website Distribution:

The website is distributed via Cloudfront. CloudFront has been configured to retrieve and distribute website files.

<h3>S3Bucket-proj1-staticwebsite:</h3>


<a href = "https://s3.console.aws.amazon.com/s3/buckets/proj1-staticwebsite?region=us-east-1&tab=objects" target = "_blank"> Proj1-StaticWebsite </a>

<h3>CloudFront Distribution:</h3>

<a href = "https://d5ltfgkw9qpou.cloudfront.net" target = "_blank">CloudFront Distribution</a>


<h3>Site URL :</h3>

<a href = "http://proj1-staticwebsite.s3-website-us-east-1.amazonaws.com/#" target = "_blank">Ahmed Aldomany Travelog</a>

<img src = "./website overview.png">
