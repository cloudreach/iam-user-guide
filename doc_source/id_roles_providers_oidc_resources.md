# Additional Resources for Web Identity Federation<a name="id_roles_providers_oidc_resources"></a>

The following resources can help you learn more about web identity federation:

+ [Amazon Cognito Identity](http://docs.aws.amazon.com/mobile/sdkforandroid/developerguide/cognito-auth.html) in the *AWS Mobile SDK for Android Developer Guide* and [Amazon Cognito Identity](http://docs.aws.amazon.com/mobile/sdkforios/developerguide/cognito-auth.html) in the *AWS Mobile SDK for iOS Developer Guide*\.

+ The [Web Identity Federation Playground](https://web-identity-federation-playground.s3.amazonaws.com/index.html) is an interactive website that lets you walk through the process of authenticating via Login with Amazon, Facebook, or Google, getting temporary security credentials, and then using those credentials to make a request to AWS\. 

+ The entry [ Web Identity Federation using the AWS SDK for \.NET](http://aws.amazon.com/blogs/developer/web-identity-federation-using-the-aws-sdk-for-net/) on the AWS \.NET Development blog walks through how to use web identity federation with Facebook and includes code snippets in C\# that show how to call `AssumeRoleWithWebIdentity` and how to use the temporary security credentials from that API call to access an S3 bucket\. 

+ The [AWS SDK for iOS](https://aws.amazon.com/sdkforios/) and the [AWS SDK for Android](https://aws.amazon.com/sdkforandroid/) contain sample apps\. These apps include code that shows how to invoke the identity providers and then how to use the information from these providers to get and use temporary security credentials\. 

+ The article [Web Identity Federation with Mobile Applications](http://aws.amazon.com/articles/4617974389850313) discusses web identity federation and shows an example of how to use web identity federation to get access to content in Amazon S3\. 