# fw\_service

This defines a service that can be added to your firewall using:

    firewall-cmd --add-service=<servicename>

## Example

    - role: fw_service
      service_name: nova-api
      service_description: nova api
      service_ports:
        - protocol: tcp
          port: 8773
        - protocol: tcp
          port: 8774
        - protocol: tcp
          port: 8775

