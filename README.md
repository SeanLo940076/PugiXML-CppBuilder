# PugiXML-CppBuilder
A guide for setting up PugiXML in C++ projects.

## Installation Steps

#### Option 1: Download and Build from Source
1. Download the latest version of PugiXML. You can download it from the [official GitHub repository](https://github.com/zeux/pugixml), the [official website](https://pugixml.org/), or directly access the archive for version 1.14 [here](https://github.com/zeux/pugixml/releases/download/v1.14/pugixml-1.14.tar.gz).

2. **Extract the archive and move it to your Documents directory:**
    ```bash
    unzip pugixml.zip -d ~/Documents
    cd ~/Documents/pugixml
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