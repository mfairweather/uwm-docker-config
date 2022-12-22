## Install

Create three directories that we can map container volumes ```plugins```, ```themes```, and ```mu-plugins```. Does not matter where these are, but this is where your local copies of themes and plugins reside. 

Create a ```.htaccess``` and ```wp-config.php`` file in the same place you created the three directories. Leave them empty.

Create a directory and ```docker-compose.yml``` file. It does not matter where this exists or the name, organize it how it would make sense for you.

Open terminal, navigate to your ```docker-compose.yml```.

Run  ```docker compose up -d```

Go to the URL defined in the ```docker-compose.yml``` file

Install wordpress

Edit the ```wp-config.php``` file to add multisite support ```define( 'WP_ALLOW_MULTISITE', true);```

Go to wordpress and install multisite

Copy and paste the code for the ```wp-config.php``` and ```.htaccess``` files.







