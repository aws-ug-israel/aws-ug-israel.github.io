# Israel AWS User Group web site
Welcome to Israel AWS User Group Web site GitHub repository

## What we're about
The Israel chapter of Amazon Web Services User Group. The group dedicated to cloud services provided by Amazon.
  
[![](./assets/aws_il_user_group.jpeg)](https://www.meetup.com/AWS-IL/)


## Join our Slack Channel:
[![](./assets/slack_icon.png)](http://bit.ly/2ErwJa5)

## You can find us on Facebook
### For AWS News on the Facebook page 
[![](./assets/100px-F_icon.svg.png)](https://www.facebook.com/awsil/)

### For Discussions on the Facebook group
[![](./assets/100px-F_icon.svg.png)](https://www.facebook.com/groups/343057205867589/)

# Creating and adding content to Israel AWS User Group web site
The Israel AWS User Group web site is based on content from users. 
You are more than welcome to contribute.

The site is built with jekyll.

## What is Jekyll, exactly?
Jekyll is a simple, blog-aware, static site generator.
For more details: https://jekyllrb.com/

### Jekyll Installation
Jekyll is a Ruby Gem, and can be installed on most systems.
For more details: https://jekyllrb.com/docs/installation/

## Quick-start guide
Install Jekyll and Bundler gems through RubyGems
```
gem install jekyll bundler
```
Clone aws-ug-israel.github.io.git repository
``` 
git clone https://github.com/aws-ug-israel/aws-ug-israel.github.io.git
cd aws-ug-israel.github.io
```
Run `bundle install` to install missing gems
```
bundle install
```
Build the site on the preview server
```
bundle exec jekyll serve
```
Now browse to http://localhost:4000

## meetup.com API
In order to populate past meetups and upcoming meetups, we will use meetup.com API.
For more details: https://www.meetup.com/meetup_api/

### Get past meetups for 2018 and dump it into JSON file (located under _data folder)
```
curl -X GET 'https://api.meetup.com/AWS-IL/events?no_earlier_than=2019-01-01&no_later_than=2020-01-01&status=past&desc=true' > _data/past_meetups_2019.json
```

### Get upcoming meetups and dump it into JSON file (located under _data folder)
```
curl -X GET 'https://api.meetup.com/AWS-IL/events' > _data/coming_meetups.json
```