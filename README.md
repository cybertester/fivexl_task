# Tony Stark Business Card

A minimal business card website.

## Deployment

The site automatically deploys to AWS S3 + CloudFront via GitHub Actions:

- Push to `dev` branch → deploys to dev environment
- Push to `main` branch → deploys to prod environment

## Setup

1. Create GitHub environments: `dev` and `prod`
2. Add secrets to each environment:
   - `AWS_ACCESS_KEY_ID`
   - `AWS_SECRET_ACCESS_KEY`
   - `S3_BUCKET`
   - `CLOUDFRONT_DISTRIBUTION_ID`

## Local Development

Open `index.html` in your browser to view the business card locally.
