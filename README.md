# To convert images to other format using the mac os command line

mkdir jpegs
sips -s format jpeg ./*.png --out jpegs


# to run heroku
export PATH=$PATH:/usr/local/heroku/bin
heroku
heroku ps:scale web=1
python manage.py runserver

#and then open the local server in a browser


# Steps to push the files to the github repo, and then push to heroku

git add .
git commit -a -m "commit..."
git push origin master
git push heroku master

# CCLP_OS
