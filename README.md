## Progresso

```txt
.
├── app
│   ├── Channels
│   ├── Console
│   │   └── Commands
│   │       ├── Deprecated
│   │       └── SingleUse
│   ├── Events
│   ├── Exceptions
│   ├── Factories
│   │   ├── CreditsGateway
│   │   ├── Payment
│   │   ├── TextMessageService
│   │   └── User
│   │       └── InformationRequest
│   ├── Helpers
│   ├── Http
│   │   ├── Controllers
│   │   │   ├── Api
│   │   │   └── Auth
│   │   ├── Middleware
│   │   ├── Requests
│   │   ├── Resources
│   │   └── ViewComposers
│   ├── Jobs
│   ├── Listeners
│   ├── Mail
│   ├── Mocks
│   │   ├── TextMessageService
│   │   └── User
│   │       └── InformationService
│   ├── Models
│   │   ├── Traits
│   │   │   └── User
│   │   └── Translatable
│   │       ├── AdType
│   │       ├── Amenity
│   │       ├── PlaceType
│   │       └── Rule
│   ├── Notifications
│   ├── Observers
│   ├── Pipelines
│   │   └── Address
│   ├── Policies
│   ├── Presenters
│   │   └── Traits
│   ├── Providers
│   ├── Repositories
│   │   ├── InitialContact
│   │   ├── Message
│   │   ├── PropertyAd
│   │   ├── RoommateAd
│   │   └── User
│   ├── Searches
│   │   └── PropertyAd
│   │       └── Filters
│   ├── Services
│   │   ├── AdComplaint
│   │   ├── AppData
│   │   ├── AutoLogin
│   │   ├── AutoReply
│   │   ├── Booking
│   │   ├── BoostPropertyAd
│   │   ├── Chat
│   │   │   └── Helpers
│   │   ├── Coin
│   │   ├── EmailPlatform
│   │   ├── Geoname
│   │   ├── GuestLead
│   │   ├── Host
│   │   ├── Ip
│   │   ├── Location
│   │   ├── Moderation
│   │   ├── NFE
│   │   ├── NotificationAd
│   │   ├── PageTitle
│   │   ├── Payment
│   │   │   └── Methods
│   │   ├── PropertyAd
│   │   ├── PropertyAdPerformance
│   │   ├── PropertyAdResponse
│   │   ├── PropertyAdView
│   │   ├── PropertyPhoto
│   │   ├── Rental
│   │   ├── RequestHttpAd
│   │   │   └── Transformers
│   │   ├── RoommateAd
│   │   ├── Rule
│   │   ├── Score
│   │   ├── Search
│   │   ├── SearchLog
│   │   ├── Subscription
│   │   ├── SuperContact
│   │   ├── TextMessageService
│   │   ├── User
│   │   │   ├── EmailLoginService
│   │   │   ├── InformationService
│   │   │   │   ├── Http
│   │   │   │   └── PackagesProvider
│   │   │   ├── MobileVerification
│   │   │   ├── ResetPasswordService
│   │   │   ├── SocialLoginService
│   │   │   └── UserPhotoService
│   │   └── UserSecurity
│   │       ├── SecurityAlert
│   │       └── SecurityFlag
│   ├── Ssr
│   └── Traits
├── bootstrap
│   └── cache
├── config
├── database
│   ├── factories
│   ├── migrations
│   └── seeders
│       ├── Immutable
│       └── Traits
├── docker
│   ├── mysql
│   ├── nginx
│   │   └── sites
│   ├── node
│   └── php-fpm
├── laravel-echo
├── public
│   ├── ajuda
│   ├── artifacts
│   ├── css
│   │   └── pages
│   ├── fonts
│   ├── images
│   │   ├── WebQuarto _ Assets
│   │   ├── about
│   │   ├── ad_flyer
│   │   ├── amenities
│   │   ├── cities
│   │   ├── custom
│   │   ├── email
│   │   ├── host-profile
│   │   │   └── covers
│   │   ├── host_panel
│   │   ├── icons
│   │   ├── landing-districts
│   │   ├── landing-moedas
│   │   ├── landing-reserva
│   │   ├── moedas-icons
│   │   ├── moedas-onboarding
│   │   ├── my-ads
│   │   └── subscription-landing
│   ├── js
│   │   ├── pages
│   │   └── search
│   │       └── properties
│   ├── plugins
│   │   └── fileuploader
│   │       └── dist
│   │           └── font
│   ├── sounds
│   └── svg
├── resources
│   ├── assets
│   │   ├── js
│   │   │   ├── components
│   │   │   │   ├── account
│   │   │   │   │   └── edit
│   │   │   │   ├── ad
│   │   │   │   │   ├── ad-complaint
│   │   │   │   │   ├── ad-map
│   │   │   │   │   ├── ad-share
│   │   │   │   │   ├── favorite-button
│   │   │   │   │   ├── phone-block
│   │   │   │   │   └── verify-mobile
│   │   │   │   ├── app-banner
│   │   │   │   ├── auth
│   │   │   │   │   └── passwords
│   │   │   │   ├── bookings
│   │   │   │   │   └── checkout
│   │   │   │   ├── credits
│   │   │   │   ├── districts
│   │   │   │   ├── home_host
│   │   │   │   │   └── credits-modals
│   │   │   │   ├── host-profile
│   │   │   │   ├── host-subscription
│   │   │   │   ├── invitation
│   │   │   │   │   └── roommate-ad
│   │   │   │   ├── location
│   │   │   │   ├── messages
│   │   │   │   │   ├── booking-request
│   │   │   │   │   ├── emoji
│   │   │   │   │   ├── interactive-messages
│   │   │   │   │   ├── invitation
│   │   │   │   │   └── video-chat
│   │   │   │   ├── mixins
│   │   │   │   ├── modals
│   │   │   │   ├── my_ads
│   │   │   │   ├── navbar
│   │   │   │   ├── notifications
│   │   │   │   ├── pagination
│   │   │   │   ├── payments
│   │   │   │   │   ├── checkout
│   │   │   │   │   └── pricing
│   │   │   │   ├── property_ad
│   │   │   │   │   ├── detail
│   │   │   │   │   ├── district
│   │   │   │   │   ├── form
│   │   │   │   │   ├── invitation-form
│   │   │   │   │   └── view
│   │   │   │   ├── rental
│   │   │   │   ├── roommate_ad
│   │   │   │   │   ├── compatible-roommates
│   │   │   │   │   ├── detail
│   │   │   │   │   ├── form
│   │   │   │   │   ├── modal-form
│   │   │   │   │   └── view
│   │   │   │   ├── search
│   │   │   │   │   └── map
│   │   │   │   ├── spinner
│   │   │   │   └── translation
│   │   │   ├── constants
│   │   │   ├── factories 🟢
│   │   │   ├── helpers 🟢
│   │   │   ├── pages
│   │   │   └── search
│   │   │       └── properties
│   │   ├── lang
│   │   │   ├── components
│   │   │   │   ├── account
│   │   │   │   │   └── edit
│   │   │   │   ├── ad
│   │   │   │   │   ├── ad-complaint
│   │   │   │   │   ├── ad-map
│   │   │   │   │   ├── ad-share
│   │   │   │   │   ├── favorite-button
│   │   │   │   │   ├── phone-block
│   │   │   │   │   └── verify-mobile
│   │   │   │   ├── app-banner
│   │   │   │   ├── auth
│   │   │   │   │   └── passwords
│   │   │   │   ├── bookings
│   │   │   │   │   └── checkout
│   │   │   │   ├── credits
│   │   │   │   ├── districts
│   │   │   │   ├── home_host
│   │   │   │   │   └── credits-modals
│   │   │   │   ├── host-profile
│   │   │   │   ├── host-subscription
│   │   │   │   ├── invitation
│   │   │   │   │   └── roommate-ad
│   │   │   │   ├── location
│   │   │   │   ├── messages
│   │   │   │   │   ├── booking-request
│   │   │   │   │   ├── emoji
│   │   │   │   │   ├── interactive-messages
│   │   │   │   │   ├── invitation
│   │   │   │   │   └── video-chat
│   │   │   │   ├── mixins
│   │   │   │   ├── modals
│   │   │   │   ├── my_ads
│   │   │   │   ├── navbar
│   │   │   │   ├── notifications
│   │   │   │   ├── pagination
│   │   │   │   ├── payments
│   │   │   │   │   ├── checkout
│   │   │   │   │   └── pricing
│   │   │   │   ├── property_ad
│   │   │   │   │   ├── detail
│   │   │   │   │   ├── district
│   │   │   │   │   ├── form
│   │   │   │   │   ├── invitation-form
│   │   │   │   │   └── view
│   │   │   │   ├── rental
│   │   │   │   ├── roommate_ad
│   │   │   │   │   ├── compatible-roommates
│   │   │   │   │   ├── detail
│   │   │   │   │   ├── form
│   │   │   │   │   ├── modal-form
│   │   │   │   │   └── view
│   │   │   │   ├── search
│   │   │   │   │   └── map
│   │   │   │   ├── spinner
│   │   │   │   └── translation
│   │   │   ├── constants
│   │   │   ├── factories
│   │   │   ├── helpers
│   │   │   ├── pages
│   │   │   └── search
│   │   │       └── properties
│   │   └── sass
│   │       ├── components
│   │       └── pages
│   ├── lang
│   │   ├── en
│   │   │   └── main
│   │   └── pt-br
│   │       ├── components
│   │       ├── errors
│   │       ├── host
│   │       ├── layouts
│   │       │   └── includes
│   │       ├── main
│   │       └── profile
│   ├── macros
│   └── views
│       ├── auth
│       │   └── passwords
│       ├── bookings
│       ├── components
│       ├── credits
│       ├── districts
│       ├── email
│       ├── errors
│       ├── host
│       ├── layouts
│       │   └── includes
│       ├── main
│       ├── messages
│       ├── payments
│       ├── profile
│       ├── properties
│       │   ├── components
│       │   └── pdf
│       ├── rentals
│       ├── roommates
│       │   └── components
│       ├── search
│       │   └── components
│       ├── subscriptions
│       └── universities
├── routes
└── storage
    ├── app
    │   ├── documents
    │   │   └── users
    │   │       ├── 2023-08
    │   │       └── 2023-09
    │   ├── photos
    │   │   ├── property_ads
    │   │   │   ├── normal
    │   │   │   │   ├── 2023-08
    │   │   │   │   └── 2023-09
    │   │   │   └── thumb
    │   │   │       ├── 2023-08
    │   │   │       └── 2023-09
    │   │   └── users
    │   │       ├── 2023-08
    │   │       └── 2023-09
    │   └── public
    ├── debugbar
    │   ├── sessions
    │   └── views
    ├── logs
    └── scripts

351 directories
```

## Passo 1: Instalação do Sublime

🟢 [Instalação do editor de código](/src/Sublime.md)

### Passo 2: Adição de traduções aos arquivos Blade

Acesse abaixo a documentação de referência para realizar a tradução dos arquivos:

🟢 [Adição de traduções no projeto](/src/Execução.md)
