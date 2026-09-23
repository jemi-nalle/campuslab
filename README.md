Jemina ja Minja (ei ehditty tekemään, kuin vain 2 harjoitukseen asti)

Harjoitus 2 - Laitetietojen kerääminen

Kerättävät tiedot:

hostname:
R1 ja R2

IOS-versio:
[r1] = "16.09.06"
[r2] = "16.09.06"

sarjanumero:
[r1] = "FGL2426LCN9"
[r2] = "FGL2426LDXH"

interfacet:
ok: [r1] => {
    "ansible_net_interfaces": {
        "GigabitEthernet0/0/0": {
            "bandwidth": 1000000,
            "description": null,
            "duplex": "Full",
            "ipv4": [
                {
                    "address": "192.168.100.11",
                    "subnet": "24"
                }
            ],
            "lineprotocol": "up",
            "macaddress": "f86b.d9b7.23b0",
            "mediatype": "RJ45",
            "mtu": 1500,
            "operstatus": "up",
            "type": "ISR4221-2x1GE"
        },
        "GigabitEthernet0/0/1": {
            "bandwidth": 1000000,
            "description": null,
            "duplex": "Full",
            "ipv4": [
                {
                    "address": "172.16.0.1",
                    "subnet": "30"
                }
            ],
            "lineprotocol": "up",
            "macaddress": "f86b.d9b7.23b1",
            "mediatype": "RJ45",
            "mtu": 1500,
            "operstatus": "up",
            "type": "ISR4221-2x1GE"
        }
    }
}
ok: [r2] => {
    "ansible_net_interfaces": {
        "GigabitEthernet0/0/0": {
            "bandwidth": 1000000,
            "description": null,
            "duplex": "Full",
            "ipv4": [
                {
                    "address": "10.10.10.1",
                    "subnet": "24"
                }
            ],
            "lineprotocol": "up",
            "macaddress": "f86b.d9b7.44e0",
            "mediatype": "RJ45",
            "mtu": 1500,
            "operstatus": "up",
            "type": "ISR4221-2x1GE"
        },
        "GigabitEthernet0/0/1": {
            "bandwidth": 1000000,
            "description": null,
            "duplex": "Full",
            "ipv4": [
                {
                    "address": "172.16.0.2",
                    "subnet": "30"
                }
            ],
            "lineprotocol": "up",
            "macaddress": "f86b.d9b7.44e1",
            "mediatype": "RJ45",
            "mtu": 1500,
            "operstatus": "up",
            "type": "ISR4221-2x1GE"
        }
    }
}
