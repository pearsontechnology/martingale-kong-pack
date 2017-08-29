# Martinglae Kong Pack

**Name:** Kong

This pack provides screens that allow users to manage a Kong API Gateway instance.

**Required Endpoints:**

/api/kong should point to the admin port of the Kong instance (EG: http://kong:8001)

or

/api[/:env]/kong should point to the admin port of the Kong instance (EG: http://kong:8001)

Where :env is an optional value to route to different instances.


## Configuration Options

### env: Environment name for the instance of the plugin.


### host: Hostname or host path to the instance of the Kong API.
**Default Value:** /api/kubernetes

## Included Pages
### KongDashboard: Side Nav

<svg fill="currentColor" preserveAspectRatio="xMidYMid meet" height="64" width="64" viewBox="0 0 256 256" style="vertical-align: middle;">
  <g>
    <path
   d="M206.24 151.84l-.584-.024-.032-.48c-.12-1.52-2.36-5.624-3.216-7.072l-.416-.72 2.48-.2c-2.04-2.624-2.512-5.52-1.296-8.064 1.096-2.28 3.464-3.936 5.64-3.936.288.024 5.68.576 5.424 10.616-.256 9.6-7.184 9.88-7.976 9.88h-.024zM176 149.28c-.104.144-.184.304-.28.448-1.104 2.296-2.4 5.384-3.536 8.184 6.208-1.6 18.456-2.88 8.68 25.88-2.76 8.112-10.624 15-21.944 19.472 1.384.24 2.936.6 4.608 1.056-9.504 2.424-22.104 4.528-37.48 4.624l1.12-.224c-23.44-.016-49.08-7.728-53.536-24.936-3.472-13.44 11.744-25.056 11.888-25.168l.592-.448s-18.72-1.936-19.6-18.416c-.864-16.48 8.456-16.128 13.408-25.8 4.96-9.664 18.64-3.864 34.72-4.32 16.08-.448 17.424 1.84 32.24-1.104 14.832-2.944 32.96 7.632 41.984 20.064 8.776 12.08-9.456 15.52-12.88 20.64l.016.048zm-122.4-5.016c-.864 1.44-3.104 5.56-3.224 7.08l-.04.48-.584.016c-.8 0-7.728-.28-7.984-9.88-.264-10.04 5.136-10.592 5.36-10.608h.016c2.224 0 4.592 1.64 5.68 3.92 1.216 2.56.744 5.44-1.296 8.064l2.48.192-.424.72.016.016z"
   fill="#ABB3C9"
   id="path4"
   style="fill:#999999" />
<path
   d="M209.024 129.744h-.192c-.52 0-1.04.08-1.568.208v-1.064h.04c1.144-8.624 1.616-16.448 1.44-23.552 0-50.92-44.344-68.88-44.344-68.88v4.4c-7.76-6.24-15.248-11.016-15.248-11.016v7.216c-1.48-.88-2.864-1.68-4.16-2.384-3.872-2.6-9.496-6.616-12.4-9.808l-3.952 10.704-2.976-9.64c-1.12 3.392-11.024 9.6-11.024 9.616.024-4.456-1.328-11.568-1.328-11.568l-19.856 16-1.888-5.856S81.488 40.6 75.536 47.6v-3.4s-29.68 19.64-29.68 59.248v.24c-.32 5.44-.24 11.264.296 17.536.32 7.328.816 7.68.816 7.68v.848c-.296.024-7.224.72-6.912 12.272.184 7.04 3.824 10.048 7.064 11.04.16 5.256 3.44 58.456 71.2 62.64h19.168c67.52-4.16 71-57.008 71.184-62.56 3.28-.944 7.072-3.936 7.264-11.12.32-11.544-6.616-12.24-6.912-12.272v-.008zm-159.232 21.6h-.08c-.72 0-7.16-.264-7.408-9.384-.256-9.68 4.864-10.08 4.864-10.08 3.8 0 8.856 5.84 3.24 11.92l2.672.216s-3.12 5.344-3.28 7.328h-.008zm130.224-13.56c-.56 11.64-11.44 20.16-11.536 20.24l-.592.48.6.432c.16.12 11.88 6.224 8.4 19.68-4.456 17.28-26.112 26.096-49.6 26.096-23.464 0-45.12-8.832-49.576-26.096-3.48-13.464 8.24-19.568 8.4-19.68l.592-.448-.592-.464c-.104-.08-10.96-8.608-11.536-20.24-.32-6.72 2.816-13.184 9.312-19.224 4.4-4.08 10.288-6.144 17.544-6.144 11.024 0 21.664 4.776 25.872 7.312 4.224-2.536 14.864-7.312 25.888-7.312 7.248 0 13.144 2.064 17.544 6.16 6.48 6.032 9.624 12.504 9.296 19.2l-.016.008zm33.68 4.176c-.24 9.12-6.688 9.384-7.416 9.384h-.08c-.144-1.984-3.28-7.328-3.28-7.328l2.672-.208c-5.624-6.096-.576-11.936 3.232-11.936 0 0 5.12.416 4.856 10.08l.016.008z"
   fill="#10313F"
   id="path6"
   style="fill:#1a1a1a" />
<path
   d="M165.68 172.68c0 11.28-16.88 20.424-37.68 20.424s-37.68-9.144-37.68-20.424 16.88-20.424 37.68-20.424 37.68 9.144 37.68 20.424"
   fill="#B4BFD1"
   id="path8"
   style="fill:#999999" />
<path
   d="M71.28 112c4.896-4.36 10.368-7.84 16.984-9.36 9.544-2.24 19.664-.608 28.752 2.56 3.12 1.088 6.16 2.344 9.064 3.864 1.808.944 1.888 1.312 3.72.336 5.808-3.12 12.24-5.384 18.76-6.704 7.736-1.56 16.064-1.648 23.536 1.064 9.072 3.296 14.72 9.624 20.384 16.784-3.84-8.72-9.44-16.16-18.52-20.584-7.176-3.488-15.544-4.368-23.496-3.496-7.056.776-13.96 2.744-20.376 5.632-1.72.776-1.944.768-3.664 0a71.597 71.597 0 0 0-4.88-1.984c-3.624-1.312-7.384-2.368-11.2-3.04-8.544-1.52-17.616-1.328-25.704 1.936-10.128 4.08-16.528 12.16-20.616 21.536 2.336-2.96 4.608-5.84 7.248-8.56l.008.016"
   fill="#133B4C"
   id="path10"
   style="fill:#333333" />
<path
   d="M134.496 162c-2.912 0-6.096-1.168-7.28-1.664-1.2.496-4.376 1.68-7.296 1.68-3.68 0-9.664-1.968-9.664-1.968s-3.04-4.64 1.6-9.096c4.224-4.064 15 1.008 15 1.008h.712s10.336-4.616 15-1.016c5.12 3.952 1.584 9.088 1.584 9.088s-5.968 1.96-9.648 1.96l-.008.008zm19.552 20.064s-8.8 6.72-26.304 6.72c-17.496 0-26.296-6.72-26.296-6.72s10.08 3.488 26.456 3.488c16.368 0 26.16-3.488 26.16-3.488h-.016z"
   fill="#D6DCE6"
   id="path12"
   style="fill:#ececec" />
<path
   d="M177.336 136.496c-12.264-25.56-50.096-10.48-50.096-10.48s-37.84-15.08-50.08 10.48c0 0-.992-16.584 18.616-21.36 12.736-3.096 31.44 7.024 31.464 7.016.032 0 18.72-10.12 31.464-7.016 19.616 4.768 18.64 21.36 18.64 21.36h-.008zm-68.536 17.4l.08 2.128c-5.08-.128-9.704 2.352-13.8 4.88 3.92-3.28 8.336-6.384 13.72-7.008zm50.16 7.016c-4.16-2.864-8.8-5.2-14.128-5.12l.096-2.12c5.584.64 10.12 3.64 14.04 7.232l-.008.008z"
   fill="#99A0BA"
   id="path14"
   style="fill:#666666" />
<path
   d="M168.936 177.48c-.368-1.176-.528-2.4-.88-3.584l-.536.48c-2.672 2.352-5.808 4.264-9.056 5.816-5.84 2.8-12.224 4.512-18.688 5.392-8.56 1.168-17.456 1.08-25.976-.4-6.144-1.04-12.16-2.88-17.656-5.736-2.936-1.52-5.776-3.336-8.184-5.552-.32 1.176-.48 2.4-.8 3.576-.984-1.52-1.168-3.456-.4-5.08.72-1.52 2.584-2.92 4.44-2.6a9.513 9.513 0 0 0-1.976 1.776c-.272.336-.192.336.08.576l.512.48c.48.4.984.8 1.488 1.2 1.6 1.224 3.336 2.304 5.12 3.28 5.904 3.2 12.512 5.2 19.216 6.224 9.232 1.424 18.912 1.264 28.08-.56 6.112-1.24 12.112-3.312 17.416-6.48 1.52-.92 2.976-1.92 4.336-3.04.4-.336.8-.688 1.176-1.04.08-.064.16-.12.208-.2.104-.16.12-.12-.04-.32-.576-.72-1.336-1.36-2.12-1.864 2.224-.44 4.56 1.584 4.912 3.576.264 1.424.12 2.816-.664 4.08h-.008zm-28.64-20.296c0 1.52-1.92 2.752-4.296 2.752-2.376 0-4.296-1.24-4.296-2.752 0-1.52 1.92-2.752 4.296-2.752 2.368 0 4.296 1.224 4.296 2.752zm4.504-1.344c-.352-2.296-2.08-4.344-4.4-5.072-2.848-.88-6.032-.56-8.928-.08 2.688-1.144 6.208-1.728 9.072-.928 1.344.376 2.56 1.008 3.472 2.024.264.288.496.64.704.96.112.16 1.088 2.136.896 2.184.208 1.88-.176 3.76-1.544 5.216.56-1.416.96-2.76.72-4.304h.008zm-25.536 4.096c-2.368 0-4.288-1.24-4.288-2.752 0-1.52 1.92-2.752 4.288-2.752 2.368 0 4.288 1.224 4.288 2.752 0 1.52-1.92 2.752-4.288 2.752zm-7.92-7.28c-.88 1.136-1.488 2.384-1.576 3.816-.08 1.304.32 2.456.8 3.664-2.272-2.416-2.016-6 .112-8.4.744-.72 1.472-1.264 2.456-1.68 1.16-.464 2.48-.64 3.728-.64 2.112 0 4.384.416 6.32 1.264a30.362 30.362 0 0 0-4.584-.448c-2.56-.04-5.584.32-7.232 2.416l-.024.008z"
   fill="#10313F"
   id="path16"
   style="fill:#333333" />
<path
   d="M97.408 208.016s-1.016-4.336 7.088-2.976c8.104 1.36 17.04 4.736 17.04 4.736s.6-2.832 5.576-2.504c4.976.32 7.68 2.896 7.68 2.896s11.64-4.896 16.448-4.816c4.816.08 5.152-1.12 5.744.64.592 1.76.504 3.216 0 5.696-.504 2.48-2.88 5.296-2.88 6.984 0 1.68 3.12 11.2-1.256 11.784-4.384.6-18.656-6.72-18.656-6.72s-1.008 2.88-5.648 2.88c-4.656 0-7.104-1.936-7.104-1.936s-15.52 6.176-18.144 5.816c-2.616-.352-2.784-2.92-2.448-5.248.336-2.32 1.264-6.496.76-6.904-.504-.4-4.216-10.336-4.216-10.336l.016.008"
   fill="#61B9E8"
   id="path18"
   style="fill:#333333" />
<path
   d="M103.872 219.096s.4 4.52 4.192 4.52c3.784 0 11.896-5.92 11.896-5.92s5.408 3.792 8.344 3.792c2.928 0 5.344-3.792 5.344-3.792s17.248 2.512 21.856-3.12c4.608-5.616-1.072 4.296-1.072 4.296s3.28 10.88-.448 11.776c-3.736.88-19.24-6.368-19.24-6.368s-4.104 2.496-6.96 2.448c-2.88-.056-5.92-1.872-5.92-1.872s-16.96 6.304-19.704 5.152c-2.736-1.152-.64-9.44 1.712-10.92v.008"
   fill="#4BAAD3"
   id="path20"
   style="fill:#4d4d4d" />
<path
   d="M159.856 206.32c-.24-1.04-.928-1.84-1.96-2.32-4.784-2.24-18.176 2.984-22.992 5.008-1.52-1.904-3.92-3.12-6.64-3.12-2.704 0-5.104 1.224-6.64 3.12-4.8-2-18.24-7.248-23.016-5.008-1.04.48-1.712 1.28-1.96 2.32-1.256 5.24 2.416 11.264 3.76 13.232-.752 2.056-2.448 7.648-.384 11.04.624 1 1.864 1.44 3.52 1.44 4.44 0 11.872-3.04 18.424-6.24a8.544 8.544 0 0 0 6.32 2.76 8.5 8.5 0 0 0 6.56-3.056c6.512 3.32 13.888 6.496 18.256 6.496 1.6 0 2.784-.424 3.392-1.416 2.08-3.384.376-8.976-.368-11.04 1.336-1.96 5.008-7.984 3.744-13.232l-.016.016zm-57.216 22.8c-1.44-2.32.184-7.584.856-9.248l.304-.72-.48-.64c-1.376-1.816-4.72-7.424-3.712-11.552.032-.12.08-.24.352-.368 2.768-1.296 13.08 2 20.296 5.008a7.747 7.747 0 0 0-.336 2.24v6.736c0 .96.184 1.872.512 2.72-8.32 4-16.464 6.664-17.776 5.84l-.016-.016zm30.96-8.544c0 2.8-2.384 5.08-5.328 5.08-2.944 0-5.336-2.28-5.336-5.08v-6.72c0-2.816 2.4-5.096 5.336-5.096 2.944 0 5.328 2.28 5.328 5.088v6.736-.008zm19.408-.704c.68 1.656 2.288 6.912.92 9.2-1.36.84-9.44-1.984-17.656-6.128.24-.752.376-1.544.376-2.368v-6.72c0-.8-.128-1.56-.352-2.272 7.2-3.008 17.52-6.288 20.264-4.992.264.128.32.24.336.368 1.2 4.96-3.656 11.48-3.712 11.552l-.48.64.304.72z"
   fill="#0D252C"
   id="path22"
   style="fill:#1a1a1a" />
<path
   d="M158.208 145.416c-.8 1.648-2.176 2.816-3.888 3.256-.16.04-.304.08-.456.096-3.344.6-6.8-1.76-7.856-5.344-.52-1.816-.4-3.68.368-5.28.8-1.648 2.184-2.8 3.896-3.248 3.48-.912 7.2 1.488 8.304 5.248.536 1.808.424 3.68-.352 5.28l-.016-.008zm-55.872 3.44c-.16-.016-.32-.04-.48-.08-3.304-.704-5.464-4.16-4.912-7.856.28-1.864 1.2-3.52 2.584-4.696 1.44-1.2 3.2-1.76 4.96-1.52 3.568.48 5.96 4.08 5.376 7.944-.584 3.904-3.968 6.696-7.52 6.216l-.008-.008z"
   fill="#0B0B0B"
   id="path24" />
<path
   d="M153.44 140.544c-1.296.24-2.528-.56-2.768-1.776-.24-1.2.608-2.384 1.888-2.608 1.28-.24 2.52.56 2.76 1.76.24 1.216-.608 2.384-1.888 2.624h.008zm-48.4.376c-1.28-.272-2.08-1.472-1.784-2.672.28-1.2 1.544-1.944 2.824-1.664 1.28.272 2.08 1.472 1.784 2.672-.28 1.2-1.544 1.952-2.824 1.68v-.016z"
   fill="#FFF"
   id="path26" />
<path
   d="M156.048 145.312c-.048.16-.584 1.464-2.416 1.52-.32 0-.624 0-.912-.064h-.032l-.32-.056c-.024-.016-.056-.016-.08-.016-.112-.032-.216-.064-.32-.08-.024 0-.04 0-.048-.024-2.928-.88-3.792-4.08-3.792-4.08.104.128.24.24.344.368 2.856 3.2 7.584 2.4 7.584 2.4s0 .024-.016.032h.008zm-53.4 1.472a4.663 4.663 0 0 1-.8-.4l-.296-.176a.288.288 0 0 1-.096-.064c-.136-.096-.264-.208-.4-.32l-.048-.056-.032-.032a.991.991 0 0 1-.224-.224c-1.816-1.92-1.32-4.768-1.32-4.768.032.16.08.32.136.48 1.296 4 5.968 5.08 5.968 5.08l-.016.024c-.08.064-1.12 1.144-2.856.464l-.016-.008z"
   fill="#525365"
   id="path28" />

  </g>
</svg>
Provides a basic dashboard view of the associated Kong API Gateway.


**Path:** /kong/


### PluginsListing: Side Nav

Provides a listing of all configured plugins.

**Icon:** Plugin

**Path:** /kong/plugins


### NewPluginSelect: 

Provides the ability to select a plugin and an optional API to bind it to for configuration.

**Path:** /kong/plugin


### EditPlugin: 

Provides the ability to create or edit an existing configured plugin for either an endpoint or globally.

**Path:** /kong/plugin/:pluginName/:id

**Path:** /kong/plugin/:pluginName


### Cluster: Side Nav

Provides an overview of the current cluster.

**Icon:** Cluster

**Path:** /kong/cluster


### APIs: Side Nav

Provides a listing of configured API&#x27;s.

**Icon:** API

**Path:** /kong/apis


### APIPlugins: 

Provides a manageable listing of plugins configured on an API.

**Path:** /kong/api/:name/plugins


### APISettings: 

Provides the ability to edit the settings for a configured API.

**Path:** /kong/api/:name

**Path:** /kong/api


### APIPluginConfig: 

Provides the ability to create or edit a plugin configuration.

**Path:** /kong/api/:apiName/plugin/:pluginName/:id

**Path:** /kong/api/:apiName/plugin/:pluginName


### APISelectNewPlugin: 

Provides ability to select an API and Plugin to configure to that API.

**Path:** /kong/api/:name/plugin


### Consumers: Side Nav

Provides a listing of configured consumers.

**Icon:** Consumer

**Path:** /kong/consumers


### Consumer: 

Provides the ability to edit the settings for a configured consumer.

**Path:** /kong/consumer/:id

**Path:** /kong/consumer


### ListBasicAuth: 

Lists all Basic Auth&#x27;s associated with a configured consumer.

**Path:** /kong/consumers/:consumer/basic-auth-accounts


### EditBasicAuth: 

Provides the ability to edit the settings for a configured Basic Auth on a specific consumer.

**Path:** /kong/consumer/:id/basic-auth/:name

**Path:** /kong/consumer/:id/basic-auth


### ListOAuth2: 

Lists all OAuth 2&#x27;s associated with a configured consumer.

**Path:** /kong/consumers/:consumer/oauth2-accounts


### EditOAuth2: 

Provides the ability to edit the settings for a configured OAuth2 on a specific consumer.

**Path:** /kong/consumer/:id/oauth2/:name

**Path:** /kong/consumer/:id/oauth2


### ListHMAC: 

Lists all HMAC&#x27;s associated with a configured consumer.

**Path:** /kong/consumers/:consumer/hmac-auth-accounts


### EditHMAC: 

Provides the ability to edit the settings for a configured HMAC on a specific consumer.

**Path:** /kong/consumer/:id/hmac-auth/:name

**Path:** /kong/consumer/:id/hmac-auth


### ListKey: 

Lists all Key&#x27;s associated with a configured consumer.

**Path:** /kong/consumers/:consumer/key-auth-accounts


### EditKey: 

Provides the ability to edit the settings for a configured Key on a specific consumer.

**Path:** /kong/consumer/:id/key-auth/:name

**Path:** /kong/consumer/:id/key-auth


### ListJWT: 

Lists all JWT&#x27;s associated with a configured consumer.

**Path:** /kong/consumers/:consumer/jwt-accounts


### EditJWT: 

Provides the ability to edit the settings for a configured JWT on a specific consumer.

**Path:** /kong/consumer/:id/jwt/:name

**Path:** /kong/consumer/:id/jwt


### ListACL: 

Lists all ACL&#x27;s associated with a configured consumer.

**Path:** /kong/consumers/:consumer/acl-auth-accounts


### EditACL: 

Provides the ability to edit the settings for a configured ACL on a specific consumer.

**Path:** /kong/consumer/:id/acl-auth/:name

**Path:** /kong/consumer/:id/acl-auth


### Certificates: Side Nav

Provides a listing of available certificates.

**Icon:** Certificate

**Path:** /kong/certificates


### Certificate: 

Provides the ability to edit the settings for a configured certificate.

**Path:** /kong/certificate/:id

**Path:** /kong/certificate


### SNIs: Side Nav

provides a listing of all configured SNI&#x27;s.

**Icon:** SNI

**Path:** /kong/snis


### SNI: 

Provides the ability to edit the configuration for a given SNI.

**Path:** /kong/sni/:name

**Path:** /kong/sni



