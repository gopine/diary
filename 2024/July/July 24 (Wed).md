# July 24, 2024

Spent the morning debugging a weird issue with the new image resizing endpoint.

Turns out it was a memory leak in the image processing library.

Fixed the leak and deployed a new version.

Happy to see the monitoring metrics showing improvement.

Implemented some basic monitoring for the Lambda function using CloudWatch.

Started exploring advanced features of serverless functions such as layers.