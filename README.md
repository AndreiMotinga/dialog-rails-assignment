DialogEDU technical screening excercise for rails developer.

NOTE: treat this as more of a fizzbuzz type of coding question rather than real world application. That being said we're interested to see clean well tested code.


Develop a simple RESTful rails API blog with 2 models: articles and comments.
  endpoints should include:

    GET /articles
    GET /articles?search=foo
      should filter article to only those containing string 'foo'
    GET /articles/:id
    POST /articles
      it should validate presence of title and body
      it should validate that title is at least 10 characters long
    PUT /articles
      same as POST
    DELETE /articles/:id

    GET /comments
    GET /comments?article_id=1
      should filter comments by specific article
    GET /comments/:id
    POST /comments
      it should validate presence of necceary attributes
    PUT /comments
    DELETE /comments/:id

This is very basic rails app, so in case you have questions use your best judgment.

Requirements/hints/tips

  1. put instructions on how to run your app in projects README
  2. paginate responses where necessary
  3. We value tests. hint: we like rspec, factory-bot, shoulda-matchers etc.
  4. we're going to take a look at your schema

Feel free to use any gems, libs etc you want.

here's our take on it. https://dialog-blog.herokuapp.com

When done, send github repo link to jobs@dialogedu.com with subject rails-assignment-'your name'
