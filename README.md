# compas-scl-xsd

Contains the official IEC 61850-6 SCL XSD schemas.

## License

The XSD schemas used are distributed under their [end user license agreement](./license/CC-EULA.pdf).

## How to retrieve new version of XSD

If there is a new version, add the definition of the new version into the pom.xml file. Then run following command:

```
mvn initialize
```

If the CI fail because the validation of checksum fail, change checksum of the new XSD version. Then run same maven command.
