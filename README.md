# S3redirect

inspired by https://stuff-things.net/2017/05/03/creating-an-s3-website-redirect-from-the-cli/

- i've added the missing part to setup the route53 record 
- added a bit more customisation, to make it easier to batch multiple domains.


# Usage
./s3redirect <bucketname> <targetdomain> <protocol> <R53ZONEID>

there is a batch script to use this for multiple domains:
./batch example.list
