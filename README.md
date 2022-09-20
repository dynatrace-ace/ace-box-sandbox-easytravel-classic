# ace-box-sandbox-easytravel

This ACE-BOX external use case is an example on how to get an easy sandbox running with EasyTravel deployed!

## Components deployed

The following components get deployed:

- Dynatrace OneAgent
- EasyTravel including configuration UI and application

## Running the sandbox

Check out [ace-box documentation](https://github.com/Dynatrace/ace-box/blob/dev/docs/external-use-case.md) for more information and provite this git repo URL as the use-case!

```
use_case="https://github.com/dynatrace-ace/ace-box-sandbox-easytravel-classic.git"
```

Additionally, please make sure that Easytravel specific ports are opened on your ACE-Box instance. Easytravel configuration UI and application will be exposed on ports `8094` and `8079` respectively.
