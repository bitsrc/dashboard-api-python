# API Coverage

## [API Usage](https://dashboard.meraki.com/api_docs#api-usage)

- List the API requests made by an organization
  - GET: *Not implemented*

## [Action batches](https://dashboard.meraki.com/api_docs#action-batches)

- Create an action batch
- Return the list of action batches in the organization
- Return an action batch
- Delete an action batch
- Update an action batch

## [Admins](https://dashboard.meraki.com/api_docs#admins)

- List the dashboard administrators in this organization
- Create a new dashboard administrator
- Update an administrator
- Revoke all access for a dashboard administrator within this organization
  
## [Alert settings](https://dashboard.meraki.com/api_docs#alert-settings)

- Return the alert configuration for this network
- Update the alert configuration for this network

## [Bluetooth clients](https://dashboard.meraki.com/api_docs#bluetooth-clients)

- Return a Bluetooth client. Bluetooth clients can be identified by their ID or their MAC.
- List the Bluetooth clients seen by APs in this network
  
## [Cameras](https://dashboard.meraki.com/api_docs#cameras)

- Returns video link for the specified camera. If a timestamp supplied, it links to that time.
- Generate a snapshot of what the camera sees at the specified time and return a link to that image.
  
## [Clients](https://dashboard.meraki.com/api_docs#clients)

- Return the client associated with the given identifier.
- Provisions a client with a name and policy.
- Return the client's daily usage history.
- Return the policy assigned to a client on the network.
- Update the policy assigned to a client on the network.
- Return the splash authorization for a client, for each SSID they've associated with through splash.
- Update a client's splash authorization. 
- List the clients that have used this network in the timespan
- List the clients of a device, up to a maximum of a month ago.
- Return the client's network traffic data over time.
- Return the events associated with this client.
- Return the latency history for a client.
  
## [Config templates](https://dashboard.meraki.com/api_docs#config-templates)

- List the configuration templates for this organization
- Remove a configuration template
  
## [Content filtering categories](https://dashboard.meraki.com/api_docs#content-filtering-categories)

- List all available content filtering categories for an MX network
  
## [Content filtering rules](https://dashboard.meraki.com/api_docs#content-filtering-rules)

- Return the content filtering settings for an MX network
- Update the content filtering settings for an MX network
  
## [Devices](https://dashboard.meraki.com/api_docs#devices)

- List LLDP and CDP information for a device
- List the devices in an organization
- List the devices in a network
- Return a single device
- Return the performance score for a single device.
- Return the uplink information for a device.
- Update the attributes of a device
- Claim a device into a network
- Remove a single device
- Get the uplink loss percentage and latency in milliseconds for a wired network device.
- Reboot a device
- Blink the LEDs on a device
  
## [Firewalled services](https://dashboard.meraki.com/api_docs#firewalled-services)

- List the appliance services and their accessibility rules
- Return the accessibility settings of the given service ('ICMP', 'web', or 'SNMP')
- Updates the accessibility settings for the given service ('ICMP', 'web', or 'SNMP')
  
## [Group policies](https://dashboard.meraki.com/api_docs#group-policies)

- List the group policies in a network
- Create a group policy
- Display a group policy
- Update a group policy
- Delete a group policy
  
## [HTTP servers](https://dashboard.meraki.com/api_docs#http-servers)

- List the HTTP servers for a network
- Return an HTTP server for a network
- Update an HTTP server
- Add an HTTP server to a network
- Delete an HTTP server from a network
- Send a test webhook for a network
- Return the status of a webhook test for a network
  
## [Intrusion settings](https://dashboard.meraki.com/api_docs#intrusion-settings)

- Returns all supported intrusion settings for an MX network
- Set the supported intrusion settings for an MX network
- Returns all supported intrusion settings for an organization
- Sets supported intrusion settings for an organization
  
## [MR L3 firewall](https://dashboard.meraki.com/api_docs#mr-l3-firewall)

- Return the L3 firewall rules for an SSID on an MR network
- Update the L3 firewall rules of an SSID on an MR network
  
## [MV Sense](https://dashboard.meraki.com/api_docs#mv-sense)

- Returns an overview of aggregate analytics data for a timespan
- Returns all configured analytic zones for this camera
- Return historical records for analytic zones
- Returns most recent record for analytics zones
- Returns live state from camera of analytics zones
  
## [MX 1:1 NAT rules](https://dashboard.meraki.com/api_docs#mx-1:1-nat-rules)

- Return the 1:1 NAT mapping rules for an MX network
- Set the 1:1 NAT mapping rules for an MX network
  
## [MX 1:Many NAT rules](https://dashboard.meraki.com/api_docs#mx-1:many-nat-rules)

- Return the 1:Many NAT mapping rules for an MX network
- Set the 1:Many NAT mapping rules for an MX network
  
## [MX L3 firewall](https://dashboard.meraki.com/api_docs#mx-l3-firewall)

- Return the L3 firewall rules for an MX network
- Update the L3 firewall rules of an MX network
  
## [MX L7 application categories](https://dashboard.meraki.com/api_docs#mx-l7-application-categories)

- Return the L7 firewall application categories and their associated applications for an MX network
  
## [MX L7 firewall](https://dashboard.meraki.com/api_docs#mx-l7-firewall)

- List the MX L7 firewall rules for an MX network
- Update the MX L7 firewall rules for an MX network
  
## [MX VPN firewall](https://dashboard.meraki.com/api_docs#mx-vpn-firewall)

- Return the firewall rules for an organization's site-to-site VPN
- Update the firewall rules of an organization's site-to-site VPN
  
## [MX cellular firewall](https://dashboard.meraki.com/api_docs#mx-cellular-firewall)

- Return the cellular firewall rules for an MX network
- Update the cellular firewall rules of an MX network
  
## [MX port forwarding rules](https://dashboard.meraki.com/api_docs#mx-port-forwarding-rules)

- Return the port forwarding rules for an MX network
- Update the port forwarding rules for an MX network
  
## [Malware settings](https://dashboard.meraki.com/api_docs#malware-settings)

- Returns all supported malware settings for an MX network
- Set the supported malware settings for an MX network
  
## [Management interface settings](https://dashboard.meraki.com/api_docs#management-interface-settings)

- Return the management interface settings for a device
- Update the management interface settings for a device
  
## [Meraki auth users](https://dashboard.meraki.com/api_docs#meraki-auth-users)

- List the splash or RADIUS users configured under Meraki Authentication for a network
- Return the Meraki Auth splash or RADIUS user
  
## [Named tag scope](https://dashboard.meraki.com/api_docs#named-tag-scope)

- List the target groups in this network
- Return a target group
- Update a target group
- Add a target group
- Delete a target group from a network
  
## [NetFlow settings](https://dashboard.meraki.com/api_docs#netflow-settings)

- Return the NetFlow traffic reporting settings for a network
- Update the NetFlow traffic reporting settings for a network
  
## [Networks](https://dashboard.meraki.com/api_docs#networks)

- Return the Bluetooth settings for a network.
- Update the Bluetooth settings for a network.
- List the networks in an organization
- Return a network
- Update a network
- Create a network
- Delete a network
- Bind a network to a template.
- Unbind a network from a template.
- The traffic analysis data for this network.
- List the access policies for this network.
- List Air Marshal scan results from a network
- Combine multiple networks into a single network
- Split a combined network into individual networks for each type of device
- Return the site-to-site VPN settings of a network.
- Update the site-to-site VPN settings of a network.
  
## [OpenAPI Spec](https://dashboard.meraki.com/api_docs#openapi-spec)

- Return the OpenAPI 2.0 Specification of the organization's API documentation in JSON
  
## [Organizations](https://dashboard.meraki.com/api_docs#organizations)

- List the organizations that the user has privileges on
- Return an organization
- Update an organization
- Create a new organization
- Create a new organization by cloning the addressed organization
- Return the license state for an organization
- Return the inventory for an organization
- List the status of every Meraki device in the organization
- Delete an organization
- Claim a device, license key, or order into an organization.
- Return the uplink loss and latency for every MX in the organization from at latest 2 minutes ago
- Return the third party VPN peers for an organization
- Update the third party VPN peers for an organization
  
## [PII](https://dashboard.meraki.com/api_docs#pii)

- List the keys required to access Personally Identifiable Information (PII) for a given identifier.
- Given a piece of Personally Identifiable Information (PII), return the Systems Manager device ID(s) associated with that identifier.
- Given a piece of Personally Identifiable Information (PII), return the Systems Manager owner ID(s) associated with that identifier.
- List the PII requests for this network or organization
- Return a PII request
- Submit a new delete or restrict processing PII request
- Delete a restrict processing PII request
  
## [Radio settings](https://dashboard.meraki.com/api_docs#radio-settings)

- Return the radio settings of a device
- Update the radio settings of a device
- List the non-basic RF profiles for this network
  
## [SAML roles](https://dashboard.meraki.com/api_docs#saml-roles)

- List the SAML roles for this organization
- Return a SAML role
- Update a SAML role
- Create a SAML role
- Remove a SAML role
  
## [SM](https://dashboard.meraki.com/api_docs#sm)

- Create a new profile containing a Cisco Clarity payload
- Update an existing profile containing a Cisco Clarity payload
- Add a Cisco Clarity payload to an existing profile
- Get details for a Cisco Clarity payload
- Delete a Cisco Clarity payload.
- Create a new profile containing a Cisco Umbrella payload
- Update an existing profile containing a Cisco Umbrella payload
- Add a Cisco Umbrella payload to an existing profile
- Get details for a Cisco Umbrella payload
- Delete a Cisco Umbrella payload.
- Create a new Polaris app
- Update an existing Polaris app
- Get details for a Cisco Polaris app if it exists
- Delete a Cisco Polaris app
- Return historical records of various Systems Manager client metrics for desktop devices.
- Return historical records of various Systems Manager network connection details for desktop devices.
- Return historical records of commands sent to Systems Manager devices.
- Returns historical connectivity data (whether a device is regularly checking in to Dashboard).
- List the devices enrolled in an SM network with various specified fields and filters
- List the owners in an SM network with various specified fields and filters
- Get the profiles associated with a user
- Get the profiles associated with a device
- Get a list of softwares associated with a user
- Get a list of softwares associated with a device
- List the network adapters of a device
- List the saved SSID names on a device
- List the security centers on a device
- List the restrictions on a device
- List the certs on a device
- Add, delete, or update the tags of a set of devices
- Modify the fields of a device
- Lock a set of devices
- Wipe a device
- Force check-in a set of devices
- Move a set of devices to a new network
- Unenroll a device
- Bypass activation lock attempt
- Bypass activation lock attempt status
- List all the profiles in the network
- Return the client's daily cellular data usage history.
  
## [SNMP settings](https://dashboard.meraki.com/api_docs#snmp-settings)

- Return the SNMP settings for a network
- Update the SNMP settings for a network
- Return the SNMP settings for an organization
- Update the SNMP settings for an organization
  
## [SSIDs](https://dashboard.meraki.com/api_docs#ssids)

- List the SSIDs in a network. Supports networks with access points or wireless-enabled security appliances and teleworker gateways.
- Return a single SSID
- Update the attributes of an SSID
  
## [Security events](https://dashboard.meraki.com/api_docs#security-events)

- List the security events for a client.
- List the security events for a network
- List the security events for an organization
  
## [Splash login attempts](https://dashboard.meraki.com/api_docs#splash-login-attempts)

- List the splash login attempts for a network
  
## [Splash settings](https://dashboard.meraki.com/api_docs#splash-settings)

- Display the splash page settings for the given SSID
- Modify the splash page settings for the given SSID
  
## [Static routes](https://dashboard.meraki.com/api_docs#static-routes)

- List the static routes for this network
- Return a static route
- Update a static route
- Add a static route
- Delete a static route from a network
  
## [Switch port schedules](https://dashboard.meraki.com/api_docs#switch-port-schedules)

- List switch port schedules
  
## [Switch ports](https://dashboard.meraki.com/api_docs#switch-ports)

- List the switch ports for a switch
- Return a switch port
- Update a switch port
  
## [Switch profiles](https://dashboard.meraki.com/api_docs#switch-profiles)

- List the switch profiles for your switch template configuration
  
## [Switch settings](https://dashboard.meraki.com/api_docs#switch-settings)

- Returns the switch network settings
- Update switch network settings
  
## [Switch stacks](https://dashboard.meraki.com/api_docs#switch-stacks)

- List the switch stacks in a network
- Show a switch stack
- Add a switch to a stack
- Remove a switch from a stack
- Create a stack
- Delete a stack
  
## [Syslog servers](https://dashboard.meraki.com/api_docs#syslog-servers)

- List the syslog servers for a network
- Update the syslog servers for a network
  
## [Traffic analysis settings](https://dashboard.meraki.com/api_docs#traffic-analysis-settings)

- Return the traffic analysis settings for a network
- Update the traffic analysis settings for a network
  
## [Traffic shaping](https://dashboard.meraki.com/api_docs#traffic-shaping)

- Update the traffic shaping settings for an MX network
- Display the traffic shaping settings for an MX network
- Update the traffic shaping settings for an SSID on an MR network
- Display the traffic shaping settings for a SSID on an MR network
- Returns the available DSCP tagging options for your traffic shaping rules.
- Returns the application categories for traffic shaping rules.
  
## [Uplink settings](https://dashboard.meraki.com/api_docs#uplink-settings)

- Returns the uplink settings for your MX network.
- Updates the uplink settings for your MX network.
  
## [VLANs](https://dashboard.meraki.com/api_docs#vlans)

- List the VLANs for an MX network
- Return a VLAN
- Update a VLAN
- Add a VLAN
- Delete a VLAN from a network
- Returns the enabled status of VLANs for the network
- Enable/Disable VLANs for the given network
  
## [Webhook logs](https://dashboard.meraki.com/api_docs#webhook-logs)

- Return the log of webhook POSTs sent
  
## [Wireless health](https://dashboard.meraki.com/api_docs#wireless-health)

- Aggregated connectivity info for this network
- Aggregated connectivity info for this network, grouped by node
- Aggregated connectivity info for a given AP on this network
- Aggregated connectivity info for this network, grouped by clients
- Aggregated connectivity info for a given client on this network.
- Aggregated latency info for this network
- Aggregated latency info for this network, grouped by node
- Aggregated latency info for a given AP on this network
- Aggregated latency info for this network, grouped by clients
- Aggregated latency info for a given client on this network.
- List of all failed client connection events on this network in a given time range
  