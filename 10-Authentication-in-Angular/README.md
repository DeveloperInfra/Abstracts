# Authentication in Angular

Most modern applications require security. However, single page applications (SPAs) introduce unique challenges when it comes to authentication. In general, traditional session-based authentication isn't a good fit for stateless SPAs. A better approach is to use OAuth tokens provided by a security token service. In this talk, we are going to look at how to build Angular applications that use token-based authentication. Our security token service will be running IdentityServer, an OpenID Connect provider and OAuth 2.0 server framework for ASP.NET.

> ##[End of IdentityServer3 Maintenance](https://leastprivilege.com/2017/11/06/end-of-identityserver3-maintenance/)
> <p>On November 5, 2017, IdentityServer made the decision to stop development and maintenance of IdentityServer3. This has a couple of reasons:</p>
> - IdentityServer4 is the better OpenID Connect and OAuth 2 implementation in every aspect
> - ASP.NET Core 2 is now a mature platform
> - There is only that much time you can spend on OSS development and issue tracker support, so we decided to focus on current projects which are IdentityServer4, IdentityModel2 and oidc-client.js
> <p>This also applies to answering questions on the issue tracker – they recommend you either use <a href="https://stackoverflow.com/questions/tagged/?tagnames=identityserver3&sort=newest">StackOverflow</a> for free support, or use a <a href="https://identityserver4.readthedocs.io/en/release/intro/support.html#commercial-support">commercial</a> support option.</p>
> <p>Security vulnerabilities will be fixed ASAP of course. Please disclose them responsibly.</p>

### Downloads:
* Slides from CodeStock - [https://speakerdeck.com/developerinfra/authentication-in-angular-codestock](https://speakerdeck.com/developerinfra/authentication-in-angular-codestock)
* Slides from Enterprise Developers Guild - [https://speakerdeck.com/developerinfra/authentication-in-angular-enterprise-developers-guild](https://speakerdeck.com/developerinfra/authentication-in-angular-enterprise-developers-guild)
* Slides from Atlanta Code Camp - [https://speakerdeck.com/developerinfra/authentication-in-angular-atlanta-code-camp](https://speakerdeck.com/developerinfra/authentication-in-angular-atlanta-code-camp)
* Slides from Triangle .NET User Group - [https://speakerdeck.com/developerinfra/authentication-in-angular-triangle-net-user-group](https://speakerdeck.com/developerinfra/authentication-in-angular-triangle-net-user-group)
* Source Code
  * [Angular Applications](https://github.com/DeveloperInfra/IdentityServer3.Samples/tree/angular/source/JavaScript%20Walkthrough) (My future contribution to the IdentityServer community.)

### Resources:
* [OpenID Connect](http://openid.net/connect/)
* [OpenID Connect Libraries](http://openid.net/developers/libraries/)
* [IdentityServer](https://github.com/IdentityServer)
* [IdentityServer Samples](https://github.com/IdentityServer/IdentityServer3.Samples/)
* [OAuth for ASP.NET](https://github.com/matthewdunsdon/oauthforaspnet)
* [JSON Web Tokens](https://jwt.io/)

### Recordings:
1. ...

### Presentations:
1. [CodeStock](http://www.codestock.org/) on May 6, 2017, @ 12:55 PM
2. [Enterprise Developers Guild](https://www.meetup.com/Enterprise-Developers-Guild/events/236625664/) on May 23, 2017, @ 6:00 PM
3. [Atlanta Code Camp](https://atlantacodecamp.com/2017) on September 16, 2017, @ 10:40 AM
4. [Triangle .NET User Group](https://www.meetup.com/TRINUG/events/243777895) on October 11, 2017 @ 6:00 PM

### Inspiration:
* Because I really like Angular and want to help make it easier to adopt IdentityServer.
