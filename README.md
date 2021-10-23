# Welcome To My Website

This website was made with pure HTML, CSS, and JavaScript.
Nothing fancy, just a simple site to help others learn a bit more about me. https://andrewderse.com/

## Hosting

This website is hosted in AWS, leveraging S3. Due to the size of it, it's being hosted 100% free.
That was my biggest goal in building the website. Building it in a manner where I could not only make it ridiculously fast, 
but also incure no monthly charges for hosting it.

## AWS S3 Push Snippet

Snippet I use to push up my changes to the AWS repo:

```
aws s3 cp <filename> s3://andrewderse.com/<filename> --content-type text/html
```