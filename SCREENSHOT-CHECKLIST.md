# Evidence checklist — Lab 02

## Included in this repository

- [x] VNet overview — `screenshots/vnet-overview.png`
- [x] VNet subnets and associated NSGs — `screenshots/vnet-subnets.png`
- [x] Web VM overview — `screenshots/web-vm-overview.png`
- [x] DB VM private networking — `screenshots/db-vm-networking.png`
- [x] Web NSG rules — `screenshots/web-nsg-rules.png`
- [x] DB NSG rules — `screenshots/db-nsg-rules.png`
- [x] Successful web-to-DB ping — `screenshots/web-to-db-ping-success.png`
- [x] Web VM SSH terminal — `screenshots/web-vm-ssh-prompt.png`

## Before publishing

- [x] Redact visible subscription IDs, account identifiers, and personal/public IPs from supplied screenshots.
- [ ] Perform a final visual review of every screenshot before publishing.
- [ ] Confirm the screenshots and README match your current Azure resources.
- [ ] Do not commit `.pem` keys or other credentials.

## Scope note

Ping proves ICMP reachability; the TCP port test establishes TCP reachability. Neither proves DB login or database software installation. The default `AllowVnetInBound` rule means full least-privilege isolation was not verified.
