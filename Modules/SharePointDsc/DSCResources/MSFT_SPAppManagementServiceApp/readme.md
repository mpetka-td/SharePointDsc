# Description

This resource is used to provision and manage an instance of the App Management
Services Service Application. It will identify an instance of the app
management service application through the application display name. Currently
the resource will provision the app if it does not yet exist, and will change
the application pool associated to the app if it does not match the
configuration. Database names or server name will not be changed if the
configuration does not match, these parameters are only used for the initial
provisioning of the service application.
