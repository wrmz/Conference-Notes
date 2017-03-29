# Designing Trustable Products: Microinteractions Matter

__Speakers__:

- [Ame Elliott](http://ameelliott.com/), Design Director at [Simply Secure](https://simplysecure.org/)
- Elizabeth Goodman, Design Supervisor at [18F](http://18f.gsa.gov/) (General Services Administration)
- [Adrienne Porter Felt](http://adrienneporterfelt.com/), Lead of Chrome Usable Security Team at Google
- [Jennifer King](http://jenking.net/), PhD Candidate at UC Berkeley School of Information

The format of this talk was kind of a question and answer forum and most of the questions weren't really of value to us, but there was an overarching theme of using creative thinking to make customers feel safe in interacting with our products.

## Takeaways

- Be mindful of cues we can give subtly give the user that provokes trust rather than revokes it
- Make a site or app that _feels_ like it's the official representation of itself
- Things should just "work"
- Users should have some sense that we're protecting them _and_ their data

---

### Examples of Trust-Building

| Platform   | Threat            | Protection                |
| ---------- | ----------------- | ------------------------- |
| Browser    | Mass Surveillance | HTTPS                     |
| Site       | Phishing          | Branding                  |
| Service    | Identity Theft    | Encryption, 2-Factor Auth |
| IoT Device | Tampering         | Alerts / Notifications    |

### Trust Concerns

- Do you trust the browser?
- Do you trust the site/host?
- Do you trust who else has access to your data?
- Do you trust that the protection mechanisms work?

## How We Apply It

Firstly, we need to make sure our SSL certificates are valid AND correct. There have been cases where Firefox or Chrome specifically delineate whether a certificate is expired, broken or otherwise not properly implemented and throws a full-page (if not subtle hint) that the page the user is on is unsecured.

We need to pay special mind to how we create forms. Responses should be immediate, reassuring and not clunky.

Our products need to feel like an extension of us. They should never second guess whether they are actually on a site owned by Sheetz, which means we really ought to work on reeling in the inconsistent and very old sites that have been out there for years unchecked and unmodified.