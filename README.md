# PugiXML-CppBuilder
A guide for setting up PugiXML in C++ projects.

## Installation Steps

#### Option 1: Download and Build from Source
1. Download the latest version of PugiXML from the [official GitHub repository](https://github.com/zeux/pugixml) or from the [official website](https://pugixml.org/), and save the zip file.
    ```bash
    cd Documents
    wget https://github.com/zeux/pugixml/releases/download/v1.14/pugixml-1.14.tar.gz
    ```
2. **Extract the archive and move it to your Documents directory:**
    ```bash
    tar -xzvf pugixml-1.14.tar.gz -C ~/Documents
    cd ~/Documents/pugixml-1.14
    ```

    ```bash
    mkdir build && cd build
    cmake ..
    sudo make -j$(nproc)
    sudo make install
    ```

#### Option 2: Using a Package Manager

##### For Debian/Ubuntu:
```bash
sudo apt-get install libpugixml-dev
```