# Technology Add-on for Vectra Cognito Stream

**Author:** Vectra Networks

**Version:**

* @version@

**Supported products:**

* Vectra X Series

**Supported CIM Version:**

* &gt;=4.0.0

**Supported CIM Datamodels:**

* Certificate
* Network Resolution (DNS)
* Network Sessions
* Network Traffic
* Web

**Sourcetypes:**

* `vectra:cognito:stream`

**Add-on contains:**

* Search and Parsing-Time configuration

**Input requirements:**

* This release requires Vectra X series to send data in syslog format

## Using this Technology Add-on

* The add-on has to be installed on Search Heads
* If data is collected through Intermediate Heavy Forwarders, it has to be installed on Heavy Forwarders, otherwise on indexers
* The add-on expects a sourcetype named `vectra:cognito:stream`

## Release Notes

* **1.0.0 / 2018-11-29** mbo

  * Initial Release

* **1.0.1 / 2019-03-28** mbo

  * Minor bug fixes

* **1.0.2 / 2019-03-28** mbo

  * Minor bug fix  

* **1.0.3 / 2019-05-22** mbo

  * Minor bug fix


## Change Log

* **1.0.0 / 2018-11-29** mbo

  * Initial Release
  
* **1.0.1 / 2019-03-28** mbo

  * Typos fixed

* **1.0.2 / 2019-03-28** mbo

  * Duplicate eventtype removed


* **1.0.3 / 2019-05-22** mbo

  * Linemerging disabled
