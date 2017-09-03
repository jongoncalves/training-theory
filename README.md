# Running project locally

Install the generator and Yeoman

    npm install -g generator-keystone
    npm install -g yo

Run the generator via Yeoman

    yo keystone

Install mongodb if you don't have it yet

    brew install mongodb

Create the data dir for mongo

    mkdir -p /data/db

Make the permissions are set properly for the user running mongo

    sudo chmod 0755 /data/db && sudo chown $USER /data/db

Run the app locally

    node keystone

