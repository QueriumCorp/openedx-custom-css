# openedx-custom-css

Source files for custom CSS for the OpenEdX LMS used on (web,staging,dev).StepWiseMath.ai 

## Build Notes

These files are loaded from an S3 bucket:

1. s3://swm-openedx-us-dev-storage/static/css/swpwrxblock.css
2. s3://swm-openedx-us-staging-storage/static/css/swpwrxblock.css
3. s3://swm-openedx-us-prod-storage/static/css/swpwrxblock.css

We use the AWS S3 console to login to the 'edmex' account at AWS that is used to manage *.StepWiseMath.ai

NOTE: If you upload a new version of these CSS files to S3, you'll need to change their permission on S3 to allow public read access.
