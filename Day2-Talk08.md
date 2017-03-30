# Design Patterns for Data Sharing

__Speaker__: Sarah Gold, Director at [Projects by IF](https://projectsbyif.com/)

__Resources__: [IF Data Permissions Catalogue](https://catalogue.projectsbyif.com/)

## Takeaways

---

### The Problem

We are creating distrust with users by keeping all of our privacy policy and use of data in only one place: The huge Terms & Conditions or Privacy Policy - putting the weight of the legalities on them, rather than us. Users are becoming less trustful, and when we use their data without easily giving them the power or control they want (and deserve), we are harming the relationship we have with our customers. Breaking trust is breaking loyalty, and that results in a decrease in active users and a decline in sign-ups.

Example: [Toys that record children](http://www.myce.com/news/samsung-changes-smart-tv-privacy-policy-after-user-concerns-but-still-shares-spoken-words-with-third-parties-78598/)

Have you ever found yourself wishing you knew more about the under-workings and data collection policies of Amazon Alexa? Then again, have you taken the time to read the policies? Would you be more trustful of the company if they gave you access to controls over what you shared?

Consider that Apple's Terms & Conditions is equivalent to about a 2-hour long audio book. And to remain informed, you'd have to listen/read that each and every time they change it. This is __not__ what consent looks like.

### Considerations

We can't do much about this without a convincing set of patterns for data sharing. Just so happens, there is a [catalogue](https://catalogue.projectsbyif.com/) of patterns recently created to help with that.

Implementations of data privacy permissions ought to be __legible__, __clear__, and __secure__.

Europe is enacting a regulation set to be implemented in May 2018 called the [General Data Protection Regulation](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation) (GDPR). This is meant to give users the following rights:

- Right to be informed
- Right of access
- Right of rectification
- Right of erasure
- Right to restrict processing
- Right to data portability
- Right to object
- Rights related to automated decisions & profiling

### What Doesn't Exist that Should

A few examples from the IF catalogue linked above that provide examples of solutions to these issues are the following:

![](https://catalogue.projectsbyif.com/images/active-request.svg)

- [Active request](https://catalogue.projectsbyif.com/#active-request)
    - A person agrees to accept individual requests to share their data and makes a decision based on that request.

![](https://catalogue.projectsbyif.com/images/data-licences.svg)

- [Data licenses](https://catalogue.projectsbyif.com/#data-licences)
    - Who I give access of my data

![](https://catalogue.projectsbyif.com/images/control-of-physical-object.svg)

- [Control of physical object](https://catalogue.projectsbyif.com/#control-of-physical-object)
    - Data can only be shared with control of physical object, or physical object contains the data

![](https://catalogue.projectsbyif.com/images/geofencing.svg)

- [Geofencing](https://catalogue.projectsbyif.com/images/geofencing.svg)
    - Access is controlled depending on the physical location of the person, using something like GPS



## How We Apply It