# FeatWS

More details in https://bancodobrasil.github.io/featws/

## Premises

- Freedom to Developers and Managers
- Agility
- Low versioned Core
- Cloud Native
- MultiCloud
- Performace
- Resilience
- Agnostic
- OpenSource

## Architecture

![Arquitetura](featws-arquitetura.png)

## Repositories

### [featws-transpiler](https://github.com/bancodobrasil/featws-transpiler) 

This project is resposable for transpile the rulesheet from the web client.

### [featws-ruller](https://github.com/bancodobrasil/featws-ruller)

After the rulesheet has been transpiled, we now have to evaluate it, and that's what featws-ruller does.

### [featws-resolver-bridge](https://github.com/bancodobrasil/featws-resolver-bridge)

A "bridge" to access external resolvers that will be needed to resolve the rulesheet

### [featws-resolver-adapter-go](https://github.com/bancodobrasil/featws-resolver-adapter-go)

A library that the resolver needs to use to connect to the above project, the featws-resolver-bridge

### [featws-language-vscode](https://github.com/bancodobrasil/featws-language-vscode) 

The VScode extension of the featws language based on .ini files, .featws is used to define the conditions of the rules.

### [featws-api](https://github.com/bancodobrasil/featws-api) 

This API is responsible for talking directly to the UI, doing CRUD operations on the rulesheets.

### [featws-ui](https://github.com/bancodobrasil/featws-ui) 

The featws UI, which will consume the featwsAPI data and show the client

### [js-featws](https://github.com/bancodobrasil/js-featws) 

A FeatWS parser/serializer in JavaScript, makes .featws files readable by javascript

### [grlc](https://github.com/bancodobrasil/grlc) 

[TODO] Lorem ipsum dolor

### [featws.tmbundle](https://github.com/bancodobrasil/featws.tmbundle) 

[TODO] Lorem ipsum dolor



