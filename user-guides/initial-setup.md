# Initial Setup

## Binary File

In order for you to interact with the ReapChain main network, you will need to have an executable binary file. Currently, this file can be downloaded here:

{% embed url="https://github.com/reapchain/mainnet/tree/main/reapchain_221230-1" %}
executable binary: reapchain\_\_Linux\_x86\_64.tar.gz, reapchain\_\_Darwin\_amd64.tar.gz
{% endembed %}

Once downloaded, check the integrity of the binary file:

```
md5sum reapchain_Linux_x86_64.tar.gz
md5sum reapchain_Darwin_amd64.tar.gz
```

Your output must match the one shown below:

```
d571fe6855f2175623815b9d3fa92280  reapchain_Linux_x86_64.tar.gz
f47ff4537206e026075535c6119f03a6  reapchain_Darwin_amd64.tar.gz
```

If you want to compile your own binary package, please visit the Developers Guide section.

You can uncompress the binary file with this command:

```
tar -xvf reapchain_Linux_x86_64.tar.gz
tar -xvf reapchain_Darwin_amd64.tar.gz 
```

Once downloaded and uncompressed, please execute the following command to make the binary file executable

```
chmod +x reapchaind
```
