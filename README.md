# Learn Ruby on Rails Graphql
Source : Dev.to post - [GraphQL Ruby(Class-based API)](https://dev.to/ksato1995/graphql-rubyclass-based-api-523n)

## Setup
```bash
$ git clone git@github.com:achmiral/learn-rails-graphql.git
$ cd learn-rails-graphql
$ bundle install
$ rails db:migrate
```
# Query and Mutation
### Get All Post
```graphql
{
  post{
    id
    title
    description
    comments
  }
}
```

### Get Single Post
```graphql
{
  post(id:1){
    id
    title
    description
    comments
  }
}
```
