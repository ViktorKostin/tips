### Ubuntu
#### node
```bash
sudo apt install -y build-essential

# installs NVM (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

# download and install Node.js
nvm install 20

# verifies the right Node.js version is in the environment
node -v # should print `v20.12.1`

# verifies the right NPM version is in the environment
npm -v # should print `10.5.0`
```

#### java
```bash
sudo add-apt-repository ppa:openjdk-r/ppa 
sudo apt-get update 
sudo apt-get install openjdk-8-jdk 
```

#### Android Studio
1. download android studio: https://developer.android.com/studio
2. ```bash
   sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386
    ```
3. ```bash
   tar -xf android-studio-2023.2.1.24-linux.tar.gz
   sudo mv ./android-studio /usr/local/android-studio
   cd /usr/local/android-studio/bin/
   sudo ./studio.sh
    ```

#### Add android studio to launcher
```
Android Studio -> Tools -> Create Desktop Entry
```

#### Tools for development
```bash
npm install -g react-native-cli
npm install -g eslint
sudo apt-get install watchman
```

#### Tools for specific react-native app
```bash
npm install --save-dev @babel/core @babel/runtime
npm install --save-dev metro-react-native-babel-preset
```
