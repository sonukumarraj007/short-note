# Mongodb Installation in Mac :

## 1. Install brew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

## 2. Install
brew tap mongodb/brew

## 3. Install Mongodb Communit
brew install mongodb-community@4.0 

## 4. Create Dir
sudo mkdir -p /System/Volumes/Data/data/db

## 5. Give File Permission
sudo chown -R `id -un` /System/Volumes/Data/data/db

## 6. Check for Working
brew services run mongodb-community@4.0

## 7. Download and Install Compass
https://www.mongodb.com/try/download/compass

## 8. Goto Application and Select Compass Icon 
right click > Open

## Restart MongoDB Server

brew services run mongodb-community@4.0 start
