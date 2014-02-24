# fw\_rule

Defines a rule in your firewall.  Modifies both the active and the
persistent configuration.

## Example

    - role: fw_rule
      rule_zone: public
      rule_service: nova-api

