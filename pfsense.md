# DNS Configurations

Domain override:
add to custom options:
  local-zone: "vserver04.lan" redirect
  local-data: "vserver04.lan 86400 IN A 10.10.10.47"
