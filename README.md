# Business Documentation
Documentation for Shortcut Business Accounts. Launch your Pros on the Shortcut platform.

# **Business Setup**

Through your Shortcut Business Account, you can register new Pros, manage their settings, and service your clients.

To get started, view our [Business Platform Setup Guide](https://github.com/Shortcut-API/Concierge-API/wiki/Business-Platform-Setup-Guide) and the [Shortcut Business FAQ](https://github.com/Shortcut-API/Concierge-API/wiki/Shortcut-Business-FAQ).

To get in touch with Shortcut, please reach out to support@getshortcut.co.

### Apps

[pullConciergeServices](#pullConciergeServices)

[pullConciergeServices](#pullConciergeServices)

[pullConciergeServices](#pullConciergeServices)

[pullConciergeServices](#pullConciergeServices)

### Documentation

***

#### pullConciergeServices
View all available services. Some services are `addOnOnly`, which means that they cannot be ordered without ordering a non-`addOnOnly` service along with it.

Parameters:
* _apiKey_ (string)

Returns: Array of Service objects.
```
Service:
{
  serviceID: string,
  img: string, // URL of service image
  title: string, // Title of service
  description: string,
  addOnOnly: boolean
}
```
