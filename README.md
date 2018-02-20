# www.imogencrispe.com

This is the source code for my personal website available at www.imogencrispe.com.

My husband [Sam](https://www.github.com/tsamb) helped me set up deployment flow for the website:

1. GitHub hosts the source code in this repo.
1. Upon changes to the master branch, Circle CI deploys the code to an Amazon S3 bucket.
1. Cloudflare directs traffic from my domain name to the S3 bucket.
