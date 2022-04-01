# Kjernetjenester
Tanken er å lage en liste over tjenestene flertallet av poer har behov for å forholde seg til.

## Plattfomer/felles

### Plattformer
Nais  
[#nais](https://nav-it.slack.com/archives/C5KUST8N6), [#nais-announcements](https://nav-it.slack.com/archives/C01DE3M9YBV)
[nais docs](https://doc.nais.io)

### Aksel
Verktøykasse med relevant innhold for produktutvikling  
Blandt annet Designsystemet og securety playbook
https://aksel.nav.no

## sluttbruker
### Persondataløsningen (PDL)
Informasjon om sluttbruker.  
[#pdl](https://nav-it.slack.com/archives/C84H68ESC)  
https://pdldocs-navno.msappproxy.net/ekstern/index.html#

### brukernotifikasjoner
sms/epost til sluttbruker, vises på dittnav  
[#brukernotifikasjoner](https://nav-it.slack.com/archives/CR61BPH7G) lenke til dock i topic
Overordnet dokumentasjon: https://navikt.github.io/dittnav-brukernotifikasjoner-intro/
Teknisk dokumentasjon: https://navikt.github.io/brukernotifikasjon-docs/

### skjermingsløsningen
Oppslag om bruker er ansatt i nav
Blandt annet for bruk i tilgangskontroll  
[team org](https://teamkatalog.nav.no/team/7cb86192-a6e9-42ed-be45-421807c96618#)

### digdir-krr
Kontaktinformasjon registrert på en bruker i det offentlige kontakt og reservasjonsregistret
Inneholder også informasjon om brukeren har reservert seg mot digital komunikasjon.  
https://github.com/navikt/digdir-krr/wiki/dkif-(REST)-→-digdir-krr-proxy-(REST)
[#team-rocket](https://nav-it.slack.com/archives/C01BXHWPLR4)

### har bruker nivå 4?
Kan bruker logge inn i løsningne dine?
https://docs.digdir.no/docs/idporten/oidc/oidc_api_authlevel.html  
Finnes det en fellestjeneste for denne? burde vi ha det?

### institusjonsopphold (inst2)
[#team-rocket](https://nav-it.slack.com/archives/C01BXHWPLR4)

### medlemskap i folketrygden (medlemskap-medl-api)
[#team-rocket](https://nav-it.slack.com/archives/C01BXHWPLR4)


### inntektskomponenten
Inntektskomponenten inneholder inntektsopplysninger, som kommer fra EDAG Felles Forvaltning (EFF) via ELSAM, samt brukeroppgitte og beregnede inntekter, som kommer inn via en NAV-intern webservice.
### Skatte Inntektsgrunnlag (sigrun)
leverer data som:
Summertskattegrunnlag, Beregnetskatt, Hendelsesliste

## arbeidsgivere
### Arbeidstaker og arbeidsgiver registeret
aareg-services

### Enhetsregisteret
ereg-services
Se også [Brønnøysundregsitrene](https://www.brreg.no/produkter-og-tjenester/apne-data/)

## veileder

### NAV Organization Master  (NOM)
https://navikt.github.io/nom/  
NOM skal inneholde og dele autoritativ informasjon om hvordan NAV er organisrt og hvem som jobber for NAV. Kilde for kontakinformasjon til veiledere og navansatte

### axsys
Hvilket veiledere som har tilgang til hvilket enhet og tema.

### norg
NORG som er rutingmaster i NAV og som inneholder alle navenheter som det rutes oppgaver til.

## Sikkerhet

### Security blueprints
Eksempler på hvordan man kan komme i gang med en del sikkerhetsrelaterte greier
[Security blueprints](https://security.labs.nais.io/)

### Azure AD
[Hvordan få personlig trygdeetaten-bruker](https://github.com/navikt/devuser-check/blob/main/README.md#faq)
[Hvordan få lesetilgang](https://github.com/navikt/azure-ad-self-service/blob/main/DirectoryRead/README.md) til Azure AD test og prod

[Users Prod](https://portal.azure.com/#blade/Microsoft_AAD_IAM/UsersManagementMenuBlade/MsGraphUsers) [Groups prod](https://portal.azure.com/#blade/Microsoft_AAD_IAM/GroupsManagementMenuBlade/AllGroups) [Applications prod](https://portal.azure.com/#blade/Microsoft_AAD_IAM/StartboardApplicationsMenuBlade/AppAppsPreview)



## Test

### Dolly
opprette test sluttbrukere
https://dolly.ekstern.dev.nav.no/

### Ida
Oprrette test veiledere
https://ida.intern.nav.no