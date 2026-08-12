


<div align="center">

# `tp3x` — homelab & infrastructure enthusiast

```text
╭──────────────────────────────────────────────────────────────╮
│  $ ping -c 1 redacted-node                                    │
│  PING redacted-node.local (REDACTED) 56(84) bytes of data.    │
│  64 bytes from REDACTED: icmp_seq=1 ttl=64 time=0.0xx ms      │
│                                                               │
│  --- redacted-node ping statistics ---                        │
│  1 transmitted, 1 received, 0% packet loss                    │
│                                                               │
│  [ CLUSTER ]  STATUS: ONLINE  •  3 NODES AVAILABLE            │
╰──────────────────────────────────────────────────────────────-╯
```

*Stavím, provozuji a vylepšuji vlastní infrastrukturu — od virtualizace přes kontejnery až po služby pro herní servery.*

</div>

---

## `cluster --status`

```text
┌──────────┬──────────┬──────────────┬─────────────────────────┐
│ NODE     │ STATUS   │ ROLE         │ ACCESS                  │
├──────────┼──────────┼──────────────┼─────────────────────────┤
│ MAIN-01  │ ONLINE   │ CONTROL      │ AUTHORIZED              │
│ NODE-02  │ ONLINE   │ COMPUTE      │ AUTHORIZED              │
│ NODE-03  │ ONLINE   │ STORAGE      │ RESTRICTED / REDACTED   │
└──────────┴──────────┴──────────────┴─────────────────────────┘
```

## `whoami`

Ahoj! Jsem **tp3x**. Zajímám se o self-hosting, serverovou infrastrukturu a automatizaci. Rád zkouším, jak propojit stabilní homelab, přehlednou správu služeb a bezpečný provoz v jeden funkční celek.

```bash
$ cat /etc/interests
virtualization  containers  storage  networking  game-hosting
```

## `stack --overview`

| Oblast | Technologie a témata |
|---|---|
| Virtualizace | Proxmox VE, virtuální stroje (VMs), Linux |
| Storage | TrueNAS, sdílené úložiště, zálohování |
| Kontejnery | Docker, Docker Compose, image management |
| Herní infrastruktura | Pelican Panel, správa instancí a služeb |
| Síť a provoz | DNS, reverse proxy, monitoring, základní hardening |
| Automatizace | Bash, Git, vlastní skripty a opakovatelné deploymenty |

## `project --current`

```text
[PROJECT]  REDACTED
[STATE]    IN PROGRESS
[FOCUS]    Infrastructure • automation • reliable services
[ACCESS]   CONFIDENTIAL 🔒
```

Aktuálně pracuji na projektu **REDACTED** — infrastrukturním projektu zaměřeném na spolehlivý provoz, automatizaci a rozšiřitelnou architekturu. Další detaily zatím zůstávají pod zámkem.

## `status`

- `UPTIME` — vždy je co optimalizovat
- `BACKUPS` — nejsou volitelné
- `DOCS` — infrastruktura má být srozumitelná i za půl roku
- `LEARNING` — další technologie je vždy jen jeden lab od vyzkoušení

<div align="center">

```text
[ root@homelab ~ ]# echo "build • break • learn • improve"
build • break • learn • improve
```

</div>
