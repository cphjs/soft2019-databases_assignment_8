# Assignment 8


The master databases IP address is: 167.99.214.12

You can set up the slave using the following command, just change the `MASTER_PASSWORD` you received with this submission:
```
CHANGE MASTER TO MASTER_HOST='167.99.214.12',MASTER_USER='slave_user', MASTER_PASSWORD='replace me'
```

And then start running it using
```
START SLAVE;
```
