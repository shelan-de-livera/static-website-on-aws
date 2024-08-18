# Static Website on AWS

This project sets up a static website using Amazon S3, secured and accelerated by CloudFront, with automated deployment via AWS CodePipeline.

Visit the live website at: [www.shelandelivera.com](https://www.shelandelivera.com)


## Features

- **Static Website Hosting:** The site is hosted on Amazon S3.
- **Secure and Fast Delivery:** CloudFront is used to deliver content securely over HTTPS, with caching to speed up load times.
- **CI/CD Pipeline:** Automated deployments are handled by AWS CodePipeline.


## Troubleshooting

- **CloudFront Caching:** If changes don't appear immediately, you might need to invalidate the cache.
- **DNS Propagation:** DNS changes could take a few hours to propagate.
