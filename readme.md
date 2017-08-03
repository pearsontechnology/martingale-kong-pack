# Martinglae Kong Pack

**Name:** Kong

This pack provides screens that allow users to manage a Kong API Gateway instance.

**Required Endpoints:**

/api/kong should point to the admin port of the Kong instance (EG: http://kong:8001)


## Included Pages
### KongDashboard: Side Nav

Provides a basic dashboard view of the associated Kong API Gateway.

**Icon:** Dashboard

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

**Path:** /kong/api/:name/plugin/:pluginName/:id

**Path:** /kong/api/:name/plugin/:pluginName


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



