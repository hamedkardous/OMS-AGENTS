
# Operations Management Suite Agent for Linux & Windows

## Quick Install guide Linux
Run the following commands to download the omsagent, validate the checksum, and install+onboard the agent. *Commands are for 64-bit*. The Workspace ID and Primary Key can be found inside the OMS Portal under Settings in the **connected sources** tab.
```
$> wget https://raw.githubusercontent.com/Microsoft/OMS-Agent-for-Linux/master/installer/scripts/onboard_agent.sh && sh onboard_agent.sh -w <YOUR OMS WORKSPACE ID> -s <YOUR OMS WORKSPACE PRIMARY KEY>
```

## Quick Install guide Windows

## [Download Script](https://github.com/hamedkardous/OMS-AGENTS/blob/master/OMSInstallAgent.ps)

You need to run the script as an administrator, and you will also need internet access from the server to download the files. However, if you don´t have internet access you could always download the agent somewhere else and copy it to the folder C:\Source and the agent would be installed by the script. Then you could still use the OMS gateway to communicate with OMS.

See below for what it looks like running the script;

![alt text](https://i1.wp.com/media.orneling.se/2017/01/1-1.jpg?resize=620%2C155&ssl=1)

Now when the installation is done, you can check out the properties of the agent in the Control Panel under “System and Security”. Hopefully you will see what I see below, and you will very soon see your server in the OMS workspace.

![alt text](https://i0.wp.com/media.orneling.se/2017/01/2-1.jpg?w=550&ssl=1)
