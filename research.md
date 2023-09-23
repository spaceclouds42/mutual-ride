# research
a document to collect existing solutions to the rideshare problem to help guide this project

## existing rideshare programs
- [LibreTaxi](https://github.com/ro31337/libretaxi)
    - promising place to start
    - communicates over telegram
    - provides spontaneous rides
- [Cyber Hike](https://github.com/stateless-minds/cyber-hike)
    - possibly even more promising starting place than LibreTaxi
    - communications over ipfs (which is _awesome_ but it seems UCF blocks ipfs??)
- [Company Carpool](https://www.companycarpool.com/#how-it-works) // [icare](https://github.com/diowa/icare)
    - uses centralized database (i think?)
    - provides regularly scheduled rides (i think original idea was a tool for carpooling to/from work)
- [TwoGo](https://www.twogo.com)
    - centralized, proprietary, requires account creation
    - having a community requires payment
    - decent web ui, didn't try the android app but screenshots look nice
    - has spontaneous and scheduled rides
- [Covoiturage Libre](https://github.com/covoiturage-libre/covoiturage-libre)
    - "aims at providing a free, non-profit carpooling service for the shared economy, with no for-profit company controlling the service"
    - archived since 2019
- [PÜL](https://github.com/FiberJW/pul)
    - "carpooling app designed for students to help each other get more involved in their community"
    - archived since 2018
- [Erkab](https://github.com/erkab/erkab-web-app)
    - "ride sharing website designed specifically for college students"
    - inactive since 2018, broken links
- [MY-RIDE](https://github.com/othreecodes/MY-RIDE)
    - centralized server
    - inactive since 2019, broken links
- [ridesharing-uber-lyft app](https://github.com/amitshekhariitbhu/ridesharing-uber-lyft-app)
    - kotlin my beloved
    - seems to be a teaching resource by a programming tutor?
    - good looking frontend application (although webapp feels like it would be a better path for cross-platform)
- [Lyff](https://github.com/akashlevy/Lyff)
    - not too relevant, specific tool for Lyft, but i thought it was a pretty cool thing
    - "Sometimes, you find yourself without Internet or data and really need to call a Lyft. Lyff lets you call a Lyft with just a quick phone call!"

## networking
- [Wesh Network](https://berty.tech/wesh)
- [Signal](https://github.com/signalapp/libsignal)
    - requires reliance on the signal server
    - secure
    - would need to figure out how to have global channel, similar to the libretaxi all channel
        - don't want to rely on having a server running a bot
    - [signal-cli-rest-api](https://github.com/bbernhard/signal-cli-rest-api)
    - [signal-cli](https://github.com/AsamK/signal-cli)
    - [signal-bot](https://github.com/aaronetz/signal-bot)
    - [libsignal-serive-java](https://github.com/signalapp/libsignal-service-java)
- IPFS
    - only the coolest peer to peer content addressed network to exist