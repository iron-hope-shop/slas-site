- [x] panda musk
- [x] essence of musk ox
- [x] platypus balm
- [x] whale smegma
- [x] balsamic urine
- [x] skunk oil
- [x] vulcan sweat
- [x] nurse tears
- [x] cologne de craig


# debug
rm -rf _site rm -rf .jekyll-cache rm .jekyll-metadata
docker-compose up

# deploy
gcloud config list
gcloud config set project slas-site
gcloud app deploy