## Change Log

### v1.10.0 (2018/08/15 17:57 +00:00)
- [#22](https://github.com/sbender9/signalk-venus-plugin/pull/22) feature: provide status to the server (@sbender9)

### v1.9.0 (2018/08/11 16:45 +00:00)
- [#21](https://github.com/sbender9/signalk-venus-plugin/pull/21) feature: allow the signalk path name for the relays to be configured (@sbender9)

### v1.8.0 (2018/07/01 20:09 +00:00)
- [#19](https://github.com/sbender9/signalk-venus-plugin/pull/19) fix: send out null deltas for unknown values (@sbender9)
- [#20](https://github.com/sbender9/signalk-venus-plugin/pull/20)  feature: add ESS mode for solar chargers (@sbender9)

### v1.7.0 (2018/05/29 21:22 +00:00)
- [#18](https://github.com/sbender9/signalk-venus-plugin/pull/18) feature: allow the poll interval to be configured (@sbender9)

### v1.6.1 (2018/05/25 01:53 +00:00)
- [#17](https://github.com/sbender9/signalk-venus-plugin/pull/17) fix: tank type names were not correct per the spec (@sbender9)

### v1.6.0 (2018/04/18 13:54 +00:00)
- [#16](https://github.com/sbender9/signalk-venus-plugin/pull/16) feature: added /ConsumedAmphours as electrical.batteries.{instance}.capacity.consumedCharge (@sbender9)

### v1.5.3 (2018/04/16 14:25 +00:00)
- [#15](https://github.com/sbender9/signalk-venus-plugin/pull/15)  fix: store /Dc/1/Voltage under batteries.{instance}-second.voltage (@sbender9)

### v1.5.2 (2018/03/21 22:32 +00:00)
- [#14](https://github.com/sbender9/signalk-venus-plugin/pull/14) fix: crash when an alarm is on (@sbender9)

### v1.5.0 (2018/03/19 18:47 +00:00)
- [#13](https://github.com/sbender9/signalk-venus-plugin/pull/13) change: updated to latest server PUT api's (@sbender9)

### v1.4.0 (2018/03/14 00:35 +00:00)
- [#12](https://github.com/sbender9/signalk-venus-plugin/pull/12) chore: change relays paths to closer match current spec RFC (@sbender9)
- [#11](https://github.com/sbender9/signalk-venus-plugin/pull/11) feature: add support to switch relays using PUT (@sbender9)

### v1.3.0 (2018/02/28 01:39 +00:00)
- [#10](https://github.com/sbender9/signalk-venus-plugin/pull/10) Add reconnecting to remote dbus (@tkurki)

### v1.2.0 (2018/02/23 04:06 +00:00)
- [#8](https://github.com/sbender9/signalk-venus-plugin/pull/8) add polling of dbus (@mpvader)

### v1.1.3 (2018/02/19 03:36 +00:00)
- [#5](https://github.com/sbender9/signalk-venus-plugin/pull/5) fix timer reset when lost dbus, smaller refactorings and fixes (@tkurki)
- [#3](https://github.com/sbender9/signalk-venus-plugin/pull/3) add ipk files & instructions for installing (@mpvader)
- [#2](https://github.com/sbender9/signalk-venus-plugin/pull/2) README.md: update instructions & remove signalk basics (@mpvader)
- [#1](https://github.com/sbender9/signalk-venus-plugin/pull/1) Multiple updates (@sbender9)