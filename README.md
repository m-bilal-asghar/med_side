# The Med Side

##### Prerequisites

The setups steps expect following tools installed on the system.

- Github
- Ruby [3.1.0]
- Rails [7.1.2]

##### 1. Check out the repository

```bash
git clone https://github.com/m-bilal-asghar/med_side.git
```

##### 2. Move into the folder

Run the following command to move into the project.

```ruby
cd med_side
```


##### 3. Create and setup the database

Run the following commands to create and setup the database.

```ruby
bundle exec rake db:create
bundle exec rake db:setup
```

##### 4. Start the Rails server

You can start the rails server using the command given below.

```ruby
bundle exec rails s
```

And now you can visit the site with the URL http://localhost:3000
