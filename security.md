1. What information does this feature expose, and for what purposes?
    * It does not intentionally expose any information, it just blocks ad scripts from using certain APIs. From a security perspective, it is possible for script to detect that some scripts do have access to an api (behind a prompt) while others do not (ad scripts).
1. Do features in your specification expose the minimum amount of information necessary to implement the intended functionality?
    * Yes
1. Do the features in your specification expose personal information, personally-identifiable information (PII), or information derived from either?
     * No
1. How do the features in your specification deal with sensitive information?
     * NA
1. Does data exposed by your specification carry related but distinct information that may not be obvious to users?
     * No
1. Do the features in your specification introduce state that persists across browsing sessions?
     * No
1. Do the features in your specification expose information about the underlying platform to origins?
     * The opposite, it prevents exposure of platform information.
1. Does this specification allow an origin to send data to the underlying platform?
     * No
1. Do features in this specification enable access to device sensors?
     * The opposite, it prevents access to device sensors.
1. Do features in this specification enable new script execution/loading mechanisms?
     * No
1. Do features in this specification allow an origin to access other devices?
     * No
1. Do features in this specification allow an origin some measure of control over a user agent's native UI?
     * No
1. What temporary identifiers do the features in this specification create or expose to the web?
     * None
1. How does this specification distinguish between behavior in first-party and third-party contexts?
     * It works in either context.
1. How do the features in this specification work in the context of a browser’s Private Browsing or Incognito mode?
     * It works in normal and incognito mode
1. Does this specification have both "Security Considerations" and "Privacy Considerations" sections?
     * There is not a specification for this intervention, as it's a browser intervention.
1. Do features in your specification enable origins to downgrade default security protections?
     * No
1. What happens when a document that uses your feature is kept alive in BFCache (instead of getting destroyed) after navigation, and potentially gets reused on future navigations back to the document?
     * It continues to work as intended
1. What happens when a document that uses your feature gets disconnected?
     * No change in behavior 
1. Does your spec define when and how new kinds of errors should be raised?
     * The intervention rejects permission policy access to ad script.
1. Does your feature allow sites to learn about the user's use of assistive technology?
     * No
1. What should this questionnaire have asked?
     * Unknown
