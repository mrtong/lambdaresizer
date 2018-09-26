This repository is based on udemy's serverless-api-aws-lambda-for-java-developers
# issue shooting
It seems like maven-assembly-plugin is required. or else a "AmazonServiceException class not found" exception will be raised.
in the input json, for the url attribute it must be a valid image url for instance in my case it is
https://img3.doubanio.com/view/subject/l/public/s6127056.jpg
it is nothing to do with S3(it does not matter this image is in your S3 or not) But after testing, the image will be saved into your S3
