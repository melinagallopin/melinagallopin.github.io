instructions pour mise à jour du bucket 

Mise à jour du GIT 
git add .
git commit -m "coucou"

synchro sur S3
aws s3 sync . s3://melina-gallopin.fr --region eu-west-1


