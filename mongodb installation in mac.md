

1. /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

2. brew tap mongodb/brew

3. brew install mongodb-community@4.0 

4. sudo mkdir -p /System/Volumes/Data/data/db

5. sudo chown -R `id -un` /System/Volumes/Data/data/db

6. brew services run mongodb-community@4.0

7. https://www.mongodb.com/try/download/compass

8. right click > Open

npm init --yes

npm i mongoose