<!-- Capital One Cloud Workshop -->
# README:

## Introduction

The purpose of this workshop is to give a bit of exposure to using Amazon Web Services.

## Before the Workshop
* Sign up for an aws educate account using your student email at awseducate.com (takes up to 48 hours).
* Or Sign up for [Amazon Free Tier](https://portal.aws.amazon.com/billing/signup?nc2=h_ct&src=header_signup&redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation#/start). You will not be charged for this.

## The Workshop

### Creating an S3 bucket
1. Select `S3 service` from  `Find Services`.
1. Click on `Create Bucket`.
1. Enter any name. This will be the name of the bucket.
1. Click `Next`.
1. Click `Next`.
1. Uncheck `Block all public access`.
1. Acknoledge the terms by checking `I Acknowledge`.
1. Click `Create Bucket`

Your bucket should now be created. You should be able to find it's name in the S3 list.

### Uploading a file to your S3 bucket
1. Click on your new bucket.
1. Click `Upload`.
1. Upload [`index.html`](index.html) (or another file).
1. Click `Next`. The default settings are fine for our purposes.
1. Click `Next`. The default settings are fine for our purposes.
1. Click `Upload`.
1. The file should upload and you should be able to see the file in the bucket.
1. Click `Properties`
1. Click `Static Website Hosting`. This enables the bucket's contents to be available to public hosting.
1. Check `Use this bucket`.
1. Set the `index document` as your `index.html`.
1. Click `Save`.

Should see an endpoint under static website hosting. If you click it should open your html file.

## Domain Name Server (After Workshop):
[Link to Amazon S3 Domain Configuration]()
