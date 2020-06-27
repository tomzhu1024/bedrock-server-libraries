# bedrock-server-libraries
Necessary libraries to run vanilla Minecraft bedrock server on CentOS. Tested for server version 1.16.0.2.

## Installation

Make a folder:

```bash
mkdir bedrock-server
cd bedrock-server
```

Download and extract the server:

```bash
wget https://minecraft.azureedge.net/bin-linux/bedrock-server-1.16.0.2.zip
yum install unzip -y
unzip bedrock-server-1.16.0.2.zip
rm -f bedrock-server-1.16.0.2.zip
```

Download and extract the libraries and script:

```bash
wget https://github.com/tomzhu1024/bedrock-server-libraries/raw/master/packed.tar.gz
tar -xzvf packed.tar.gz
rm -f packed.tar.gz
chmod +x start.sh
```

Use the script to start the server:

```bash
./start.sh
```

