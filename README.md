# veladab

utility for converting a traditional Vela build object to a DAB (directed acyclical build)

## usage

Simply run the utility, providing the information required to look up the build in the Vela database.  

| key | value | description |
| --- | ----- | ----------- |
| VELA_SERVER_ADDR | https://vela-server.prod.com | vela server host |
| VELA_BUILD_ORG | go-vela | vela github organization name |
| VELA_BUILD_REPO | octocat | vela github repository name |
| VELA_BUILD_BUILD_NUMBER | 1 | vela build number |
