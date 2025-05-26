# >> check how this file override or is overridden by the environment info mentionned in the compose file
{
  "version": 2,
  "logLevel": "INFO", >> INFO or DEBUG
  "registerContainerNames": true,
  "domain": "<server.lan>", >> name of the domain fore wich DPS is serving addresses
  "dpsNetwork": false, >> do not use the default dps network >> need to be checked how this affect the working of DPS
  "dpsNetworkName": "<>", >> name of the docker network used
  "dpsNetworkAutoConnect": true, >> 
  "noRemoteServers": true, >> 
  "envs": [] >>
}
