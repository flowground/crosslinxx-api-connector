# ![LOGO](logo.png) crosslinxx API **flow**ground Connector

## Description

A generated **flow**ground connector for the crosslinxx API API (version 1.0.0).

Generated from: //apidev.crosslinxx.com/v1<br/>
Generated at: 2019-09-23T12:48:09+00:00

## API Description

API für die Interaktion mit crosslinxx Prozessen.<br/>

## Authorization

Supported authorization schemes:
- Basic Authentication

## Actions

### Liefert Access und Refresh Token

*Tags:* `interfacerequest-controller`

### error

*Tags:* `basic-error-controller`

### error

*Tags:* `basic-error-controller`

### error

*Tags:* `basic-error-controller`

### error

*Tags:* `basic-error-controller`

### error

*Tags:* `basic-error-controller`

### error

*Tags:* `basic-error-controller`

### error

*Tags:* `basic-error-controller`

### Liefert alle Interfacerquests zu einer bestimmten TenantId und einem Talendjobnamen

*Tags:* `interfacerequest-controller`

#### Input Parameters
* `tenantid` - _required_ - tenantid<br/>
* `talendjobname` - _optional_ - talendjobname<br/>
* `includeProcessVariables` - _optional_ - includeProcessVariables<br/>
* `requeststatus` - _optional_ - requeststatus<br/>

### Liefert die Prozessvariablen aller Interfacerequests, die am selben Tag des Requests erstellt wurden anhand des InputParameterSyncCall

*Tags:* `interfacerequest-controller`

#### Input Parameters
* `id` - _required_ - id<br/>

### Liefert einen bestimmten Interfacerequest anhand dessen ID

*Tags:* `interfacerequest-controller`

#### Input Parameters
* `includeProcessVariables` - _required_ - includeProcessVariables<br/>
* `id` - _optional_ - id<br/>

### Liefert alle Prozessvariablen anhand des InputParameterSyncCall

*Tags:* `interfacerequest-controller`

#### Input Parameters
* `id` - _required_ - id<br/>

### Aktualisiert Werte eines Interfacerequests

*Tags:* `interfacerequest-controller`

#### Input Parameters
* `id` - _required_ - id<br/>

### Liefert Informationen uber einen Prozess anhand dessen ID

*Tags:* `interfacerequest-controller`

#### Input Parameters
* `id` - _required_ - id<br/>

### Startet einen neuen crosslinxx Prozess

*Tags:* `interfacerequest-controller`

#### Input Parameters
* `processInstance` - _required_ - processInstance<br/>

## License

**flow**ground :- Telekom iPaaS / crosslinxx-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
