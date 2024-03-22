A list of awesome and open projects supporting
the  [German Digital Health Applications (DiGA)](https://www.bfarm.de/EN/Medical-devices/Tasks/DiGA-and-DiPA/Digital-Health-Applications/_node.html)
space.

### Glossary

- [DiGA](https://www.bfarm.de/EN/Medical-devices/Tasks/DiGA-and-DiPA/Digital-Health-Applications/_node.html) - Digital
  Health Applications
- [GesundheitsID](https://www.gematik.de/anwendungen/gesundheitsid) - Germany's digital identity in the health care
  space
- [TI](https://www.gematik.de/telematikinfrastruktur) - Telematik Infrastruktur
- [ePA](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/E-Health/Elektronische-Patientenakte/elektronische-patientenakte.html) -
  Germany's personal health record

## General Documentation & Normative Documents

- **[DiGA Leitfaden](https://www.bfarm.de/SharedDocs/Downloads/DE/Medizinprodukte/diga_leitfaden.html)** - the bible for
  specifications and regulations regarding DiGAs
- **[Gematik gemSpec](https://gemspec.gematik.de/)** - online portal to browse the specifications related to DiGAs and
  other bits of the TI
- **[Gematik TI Leitfaden](https://wiki.gematik.de/display/TFD)** - Gematik Wiki for all things related to TI
  implementation

## Code Validation & Invoicing

- **[diga-api-client](https://github.com/alex-therapeutics/diga-api-client)** - Java library to interact with the DiGA
  API to validate and invoice prescription codes.

## GesundheitsID

- **[OpenID Federation Specs](https://openid.net/specs/openid-federation-1_0.html)** - the standard behind the
  GesundheitsID federation
- **[TI-RelyingParty](https://github.com/BAYOOMED/TI-RelyingParty)** - simple OIDC adapter acting as Relying Party in
  the Gematik OIDC Federation (GesundheitsID) and providing standard OIDC for clients
- **[ehealthid-relying-party](https://github.com/oviva-ag/ehealthid-relying-party)** - standalone server exposing
  Germany's 'GesundheitsID' (eHealthID) as a OpenID Connect Relying Party (OIDC RP) + scripts to generate keys and
  federation registration form.

## ePA

- **[api-ePA](https://github.com/gematik/api-ePA)** - API definitions for ePA APIs
- **[api-telematik](https://github.com/gematik/api-telematik)** - API definitions for the TI in general
- **[gematik-epa-postman-collection](https://github.com/ikosta/gematik-epa-postman-collection)** - Postman-Collection
  for DiGAs to make requests to the TI-Connector and write into the ePA
- **[diga-epa-lib](https://github.com/oviva-ag/diga-epa-lib)** - Java library for Telematik-Infrastuktur (TI) via a
  Konnektor to write structured HL7/FHIR bundles for DiGA treatments into the electronic health record (ePA)
- **[epa-ps-sim](https://github.com/gematik/epa-ps-sim)** - Simplified triggering of operations provided by the ePA
  Fachmodul of the Konnektor using a REST interface.
