# cms-troubleshooting

This repo contains various links, things to try when troubleshooting issues.

## File Transfer, xrootd issues
- [Using Xrootd Service (AAA) for Remote Data Access](https://twiki.cern.ch/twiki/bin/view/CMSPublic/WorkBookXrootdService)
- [EOS quick tutorial for beginners](https://cern.service-now.com/service-portal?id=kb_article&sys_id=fae8543fc9ed05006d218776d679b74a)
- [Using Grid](https://twiki.cern.ch/twiki/bin/view/Sandbox/UsingGrid)
- [How to work with Storage Element](https://wiki.chipp.ch/twiki/bin/view/CmsTier3/HowToAccessSe)

Turn on/off xrootd Debug, can set in .bash_profile

```
alias xrddebugon='export XRD_LOGLEVEL=Debug' 

alias xrddebugoff='unset XRD_LOGLEVEL'

```
