# Privacy Statement—English Wikipedia Account Creation Assistance
Thank you for using the English Wikipedia Account Creation Assistance tool ("the Tool"). This Privacy Statement explains
how we collect, use, and dispose of the data we collect from you, as required by the [Terms of Use of the Wikimedia
Foundation Cloud Services ("WMCS") project][wmcs-tou].

Except where otherwise noted, this Privacy Statement applies to all users of the English Wikipedia Account Creation
Assistance project, including but not limited to:

- Users who are using the Tool to request that Wikipedia accounts be created for them ("Requesters").
- Established Wikipedia users who register and log in to the Tool in order to process account requests from Requesters
  ("Account Creators"). Account Creators can be further divided into the following groups, though most are members of
  any of these groups:
  - "Administrators": Also called "Tool Admins", these are Account Creators who are very trusted and have extra
    capabilities beyond what Account Creators ordinarily have, such as the ability to grant and revoke access to the
    Tool. Note that this is not the same as, nor does it imply that a user is, a [Wikipedia
    administrator][enwiki-admins].
  - "Checkusers": Account Creators who also have the [CheckUser permission on Wikipedia][enwiki-cus] and are thus highly
    trusted.
  - "Stewards": Account Creators who are also [Stewards on Wikimedia projects][meta-stewards], and are likewise highly
    trusted members of the community.
  - "Tool Roots": These Account Creators are the projects leads and are ultimately responsible for the overall
    management of the Tool. They are responsible for ensuring that the Tool is in compliance with Wikimedia Foundation
    policies and guidelines and are the only users with access to the underlying WMCS infrastructure that the Tool runs
    on.

A full list of current Account Creators can be found on the [Tool's user list][acc-users], including which of the above
groups they belong to. Account Creators are trusted, vetted members of the Wikipedia editor community who have been
granted access to the Tool by the Administrators. They are required to be in good standing with the Wikimedia
Foundation, to be 18 years of age or older, and to have signed the legally-binding [Wikimedia Foundation Confidentiality
Agreement for Nonpublic Information][wmf-confidentiality-agreement]. Account Creators are subject to an activity
requirement; if they do not use the Tool for 45 days, their access to the Tool is suspended.

## Data we collect
### From Requesters
When you use the English Wikipedia Account Creation Assistance Tool to request that an account be created for you, we
assign a unique numeric request identifier to your request. This identifier is used to allow both Account Creators to
track the status of your request and to identify it going forward. The request identifier itself conveys no personally
identifying information, but will be permanently linked to your Wikipedia account via the [user creation
log][enwiki-user-creation] if an account is created for you by an Account Creator.

The request identifier can only be used by authorized Account Creators to access the details of your account request.
Account Creators must meet the requirements noted above before they can access the Tool.

When you make an account request, we collect the following information and associate them with your request identifier:

- The username you would like to have created. We need this information in order to create your account, and to identify
  when the same account has been requested multiple times.
- The [IP address][enwiki-ip-address] of the device you are using to make your request, which may also reveal
  information about your physical location. We collect this information in order to provide support (for example, in 
  order to check if your IP address has been blocked on Wikipedia, which could prevent you from editing even with an
  account) and to identify and protect against abuse of the Tool and of Wikipedia.
- The email address you provide. We use it to contact you about your request if we require more information, as well as
  to inform you of whether your request was fulfilled or declined. We also use it to send you your temporary password
  if your account is created. Finally, we also use your email address to identify and protect against abuse of the Tool
  and of Wikipedia.
- Browser characteristics, such as your [User-Agent string][enwiki-user-agent] and [Client Hints][enwiki-client-hints].
  We collect this information in order to identify and protect against abuse of the Tool and of Wikipedia, and it cannot
  be accessed by all Account Creators. Only Checkusers, Stewards, and Tool Roots have access to this information.

Except for the username you request, all the personal information above is automatically deleted when it is no longer
needed in order to protect it, either:

1. After 15 days from when the request is initially submitted
2. When the request is fulfilled or declined

...Whichever comes _later_.

We also allow Requesters to submit a free-text comment with their request so that they may add context to their request.
This comment is visible to all Account Creators and is also permanently linked to your request identifier, as are any
internal comments left on a request by Account Creators. While these comments are not automatically deleted,
Administrators are responsible for deleting any private or personally identifying information, including types of
information not explicitly noted above, left in those requests, and we likewise encourage Requesters to avoid including
unnecessary personal information in their comments. Account Creators are prohibited from adding any Requesters' personal
information in their comments, and may be suspended from the Tool if they do so.

**Requesters should be aware of the following important information:**
1. Your real name is considered private information, **unless you include your real name in your requested username**.
   If you do not want your real name to be associated with your Wikipedia account, **do not include it in your requested
   username**. If you do choose to include your real name in your username, it will be permanently tied to your
   request identifier in the Tool, even if you later change your username, and will be visible to the entire public on
   Wikipedia itself, potentially forever. For more information, please see [Wikipedia's policy on the use of real names
   as usernames][enwiki-upol-real-names].
2. **Do not include any password as part of your account request, or in any email communication with the Account Creator
   team**. A random password will be automatically emailed to you if your account is created, and you will be able to
   change it to a password of your choice after you log in for the first time. Account Creators do not have access to
   your password, and you should never share your password with anyone.

### From Account Creators

## Data residency disclaimer
WMCS is hosted and operated in the United States. By using English Wikipedia Account Creation Assistance, you
acknowledge and understand that collection, use, storage, and other processing of your information (personal or
otherwise) as outlined in this Privacy Statement will take place in the United States. You understand that your
information also may be transferred to other countries, and that the United States and such other countries may have
different or less stringent data protection laws than your country. Furthermore, you acknowledge that your Personal
Information will be governed by this Privacy Statement, rather than the Wikimedia Foundation's Privacy Policy.

## History
For a history of changes to this Privacy Statement, please refer to the [GitHub commit
history][privacy-statement-history].

[wmcs-tou]: https://wikitech.wikimedia.org/wiki/Wikitech:Cloud_Services_Terms_of_use
[enwiki-admins]: https://en.wikipedia.org/wiki/Wikipedia:Administrators
[enwiki-cus]: https://en.wikipedia.org/wiki/Wikipedia:CheckUser
[meta-stewards]: https://meta.wikimedia.org/wiki/Stewards
[acc-users]: https://accounts.wmflabs.org/internal.php/statistics/users
[wmf-confidentiality-agreement]: https://foundation.wikimedia.org/wiki/Legal:Confidentiality_agreement_for_nonpublic_information
[enwiki-user-creation]: https://en.wikipedia.org/w/index.php?title=Special:Log&type=newusers
[enwiki-ip-address]: https://en.wikipedia.org/wiki/IP_address
[enwiki-user-agent]: https://en.wikipedia.org/wiki/User-Agent_header
[enwiki-client-hints]: https://en.wikipedia.org/wiki/HTTP_Client_Hints
[enwiki-upol-real-names]: https://en.wikipedia.org/wiki/Wikipedia:Username_policy#Real_names
[privacy-statement-history]: https://github.com/enwikipedia-acc/compliance/commits/main/privacy-statement.md
