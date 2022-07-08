# LinkCheckerDemo

Manuel integration test for LinkChecker

```
ddev start
ddev ssh
./flow site:import --package-key="CodeQ.Site"
./flow user:create admin admin Admin Admin
./flow user:addrole admin Neos.Neos:Administrator
./flow checklinks:crawl
./flow checklinks:crawlnodes
```
