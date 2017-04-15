![img](http://www.textfiles.com/underconstruction/HeHeartlandBluffs8237Photo_2000construction5_anim.gif)

# OpenEMR AWS Guide

## ☁ Overview

Our team will provide a turnkey solution for small facilities and hospitals to run their OpenEMR v5 installation in the AWS cloud. This solution will be peformant, scalable, secure (HIPAA-compliant), and cost-effective.

Many OpenEMR users host their server instances on premise and have not yet realized the benefits of cloud technologies. While users can hire a professional vendor for cloud deployment services or simply learn AWS and do it themselves, our team has identified a need for a more cost effective option.

## 🕊️ Version 1 and 1.5

This first release (codename "Dove") will use AWS services in a way that can be described as a "PaaS-buffet". This is to say that the choosen technologies will "lock" the user to many opinionated AWS services.

Services include Elastic Beanstalk, RDS, Route53, IAM, CouchDB, and Cloudwatch. This version will involve a series of numbered steps to get every step up. Automation will be done in CloudFormation in Version 1.5 to truly allow a user to "turn the key".

## 🐨 Version 2

This second release (codename "Koala") will focus on using generic services so users may choose any cloud provider they want. Ideally, users can stand up a "local cloud" should they choose to benefit from cloud technologies but want to run their own data centers.

_Note that this will most likely end up being spawned off as another repo._

## License & Credits

MIT
