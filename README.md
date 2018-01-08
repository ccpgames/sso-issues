# CCP SSO Issues
Please file issues with the CCP SSO (login.eveonline.com) in this repo!

For help or questions about using the SSO, join #sso on Tweetfleet Slack (click [here](https://www.fuzzwork.co.uk/tweetfleet-slack-invites/) to get an invite).

# Stuff being worked on currently (ETA: Q1-2018)
* Scalability and performance improvements
* [JWT token](https://jwt.io/) support (starting with internal services, will roll out to 3rd party devs once it has been stabilized internally). I'll ask for volunteers on the #sso TweetFleet slack channel once we start opening it up. We'll  need support from the ESI guys before we can open it up to 3rd party developers. SSO JWT tokens will be RS256 signed with the public key discoverable via the standard OpenID Connect discoverability endpoint.
* [OpenId Connect](http://openid.net/connect/) compatibility.
* [OAuth 2.0 Discoverability](https://tools.ietf.org/html/draft-ietf-oauth-discovery-08)
* [OAuth 2.0 PKCE](https://tools.ietf.org/html/rfc7636)
* Multiple redirect URIs for clients.
