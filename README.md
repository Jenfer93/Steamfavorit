# Steamfavorit

En applikasjon hvor vi kan dele spennende spill med våre venner. Her kan vi få oversikt over hva våre venner ønsker å spille og dele med dem hva vi selv syns ser spennende ut. 


TO DO: 
- Klar plan på hva siden trenger
    - Innloggingsside*
    - Hovedside
      - seksjon for egne favoritt spill med lenke til spillside
      - seksjon for venners favoritt spill med lenke til spillside
    - Spillside
      - Spillets navn
      - Beskrivelse
      - Pris(?)
      - Eventuell release dato
- Skal vi bruke React eller annet bibliotek?
- Farge valg
- Design

* Forslag til innloggingsside løsning fra steam-samfunn:
Steam OpenID Provider
Steam can act as an OpenID provider. This allows your application to authenticate a user's SteamID without requiring them to enter their Steam username or password on your site (which would be a violation of the API Terms of Use.) Just download an [OpenID](https://steamcommunity.com/linkfilter/?u=http%3A%2F%2Fopenid.net%2Fdevelopers%2Flibraries%2F) library for your language and platform of choice and use https://steamcommunity.com/openid as the provider. The returned Claimed ID will contain the user's 64-bit SteamID. The Claimed ID format is: https://steamcommunity.com/openid/id/<steamid>
