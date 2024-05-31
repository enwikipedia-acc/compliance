# Privacy Statement—English Wikipedia Account Creation Assistance
Thank you for using the English Wikipedia Account Creation Assistance tool ("the Tool") and project ("the Project",
"we", "our", or "us"). This Privacy Statement explains how we collect, use, and dispose of user data, as required by the
[Wikimedia Cloud Services ("WMCS") Terms of Use for Administrators and Developers][wmcs-tou-devs].

Except where otherwise noted, this Privacy Statement applies to all users of the English Wikipedia Account Creation
Assistance project, including but not limited to:

- Users who are using the Tool to request that Wikipedia accounts be created for them ("Requesters").
- Established Wikipedia users who register and log in to the Tool in order to process account requests from Requesters
  ("Account Creators"). Some Account Creators are members of one or more of the following groups, which grant them extra
  capabilities beyond what Account Creators ordinarily have:
    - "Administrators": Also called "Tool Admins", these are Account Creators who are very trusted and have extra
      administrative capabilities, such as the ability to grant and revoke access to the Tool. Note that this is not the
      same as, nor does it imply that a user is, a [Wikipedia administrator][enwiki-admins].
    - "Checkusers": Account Creators who also highly trusted, well-vetted members of the Wikipedia community, that have
      been approved by the community to have access to the [CheckUser tool on Wikipedia][enwiki-cus], an anti-abuse
      system.
    - "Stewards": Account Creators who are also [Stewards on Wikimedia projects][meta-stewards], community members who are
      extremely trusted across multiple Wikimedia wikis, who assist with cross-wiki abuse prevention and other issues.
    - "Tool Roots": These Account Creators are the Projects' leads and are ultimately responsible for the overall
      management and development of the Tool. They are responsible for ensuring that the Tool is in compliance with
      Wikimedia Foundation policies and guidelines and are the only users with access to the underlying WMCS
      infrastructure that the Tool runs on. The Tool Roots are further bound by and must adhere to the [Wikimedia Cloud
      Services ("WMCS") Terms of Use for Administrators and Developers][wmcs-tou-devs].

A full list of current Account Creators can be found on the [Tool's user list][acc-users], including which of the above
groups they belong to. Account Creators are trusted, experienced members of the Wikipedia editor community who have been
vetted by and granted access to the Tool by the Administrators. They are required to be in good standing with the
Wikimedia Foundation, to be 18 years of age or older, and to have signed the legally-binding [Wikimedia Foundation
Confidentiality Agreement for Nonpublic Information][wmf-confidentiality-agreement]. Account Creators are subject to an
activity requirement; if they do not use the Tool for 90 days, their access to the Tool is suspended.

Finally, note that the Tool is an open-source project, and as such, the code is publicly available [on
GitHub][github-waca]. Likewise, anyone can contribute code and become a developer for the Project, however, becoming a
developer does not grant access to the Tool itself (i.e., not all developers are Account Creators) and thus developers
only have access to the data collected by the Tool if they are also an approved Account Creator. Except for the Tool
Roots, developers also do not have access to the servers and other infrastructure that the Tool runs on.

## Data we collect
### From Requesters
When you use the English Wikipedia Account Creation Assistance Tool to request that an account be created for you, we
assign a unique numeric request identifier to your request. This identifier is used to allow both Account Creators to
track the status of your request and to identify it going forward. The request identifier itself conveys no personally
identifying information, but will be permanently linked to your Wikipedia account and username via the public [user
creation log][enwiki-user-creation] (amongst other locations) if an account is created for you by an Account Creator.

The request identifier can be used by authorized Account Creators to access the details of your account request. Account
Creators must meet the requirements noted above before they can access the Tool.

When you make an account request, we collect the following information and associate them with your request identifier:

- The username you would like to have created. We need this information in order to create your account, to provide
  support (for example, to identify when the same account has been requested multiple times, or if a username does not
  comply with [Wikipedia's username policy][enwiki-upol]), and to identify and protect against abuse of the Tool and of
  Wikipedia.
- The [IP address][enwiki-ip-address] of the device you are using to make your request, which may also reveal
  information about your physical location. We collect this information in order to provide support (for example, in
  order to check if your IP address has been blocked on Wikipedia, which could prevent you from editing even with an
  account) and to identify and protect against abuse of the Tool and of Wikipedia.
- The email address you provide. We use it to contact you about your request if we require more information, as well as
  to inform you of whether your request was fulfilled or declined. We also use it to send you your temporary password
  if your account is created. Finally, we also use your email address to identify and protect against abuse of the Tool
  and of Wikipedia. We require email addresses to be validated in order to process your request; this is accomplished by
  sending an automated confirmation email with a special link that must be clicked to process your request.
- Browser characteristics, such as your [User-Agent string][enwiki-user-agent] and [Client Hints][enwiki-client-hints].
  We collect this information in order to identify and protect against abuse of the Tool and of Wikipedia, and it cannot
  be accessed by all Account Creators. Only Checkusers, Stewards, and Tool Roots have access to this information.

We take reasonable measures to protect your personal information. Except for the username you request, all the personal
information above is automatically and permanently deleted from the Tool when it is no longer needed, either:

1. After 15 days from when the request is initially submitted
2. When the request is fulfilled or declined

...Whichever comes _later_.

We also allow Requesters to submit a free-text comment with their request so that they may add context to their request.
This comment is visible only to Account Creators and is also permanently linked to your request identifier, as are any
internal comments left on a request by Account Creators. While these comments are not automatically deleted,
Administrators are responsible for and endeavor to permanently remove any private or personally identifying information,
including types of information not explicitly noted above, contained in those requests when the request is closed, and
we likewise encourage Requesters to avoid including unnecessary personal information in their comments. Account Creators
are prohibited from adding any Requesters' personal information in their comments, and may be suspended from the Tool if
they do so.

In order for Account Creators to provide support to Requesters, to enforce Wikipedia policy with respect to usernames
and account creation, and in order to detect, prevent, and respond to abuse of the Tool and of Wikipedia, Account
Creators may share some of the information collected with your request with services hosted by the Wikimedia Foundation,
with other WMCS services, or with external third-party services; for example, your IP address may be used with a
third-party analysis service to determine if it is a known proxy or VPN IP address; or, if your email address is using
an uncommon service, we may look up the domain portion (the part after the `@`) in public Internet registries. In these
cases, we take care to ensure that your unique request identifier and your requested username are not shared with these
services, so that there is no way for that service to associate the information provided to it with your account request
or Wikipedia username. This data is also never automatically shared; the action must be initiated by an Account Creator
and is logged for auditing purposes.

In addition, if the Account Creators decide to fulfill your account request, your username and email will be provided to
Wikipedia in order to create your account. All Wikipedia accounts are required to have a username which is displayed
publicly, and while an email address is optional for self-created accounts, it is required for accounts created by
Account Creators. The email address associated with a Wikipedia account can be changed or removed after logging in, and
it is never revealed publicly. Note that the data deletion policy above does not apply to your username and email
address as shared with Wikipedia in the process of creating your account. While our copy of the data will be deleted,
the copy shared with Wikipedia—as well as your future interactions with Wikipedia—will be governed by the [Wikimedia
Foundation's Privacy Policy][wmf-privacy-policy]. Note that Account Creators broadly do not have any access to the
account data used by Wikipedia itself, including the email, password, IP addresses, and browser characteristics
associated with an existing Wikipedia account, with the notable exception of Checkusers who have access to some of this
data for existing Wikipedia accounts to help detect and prevent abuse of Wikipedia; please see [Wikipedia's Checkuser
policy][enwiki-cus] for more information.

Aside from the above purposes, your data will never be sold or shared with any other party or service. As noted above,
your data in the Tool is automatically and permanently deleted when it is no longer needed in order to protect it.

Account Creators are also themselves instructed to protect your personal information and are prohibited from sharing it
in any unauthorized manner, especially in any manner that may correlate your personal information with your account
request identifier or your Wikipedia username. Account Creators who violate this policy are terminated from the Project
and may face additional sanction, as prescribed by the Wikimedia Foundation.

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
3. **Requesters are required to adhere to the [Wikimedia Cloud Services End User Terms of Use][wmcs-tou-users].**

### From Account Creators
In order to use the Tool, we collect the following information from prospective Account Creators:

- A username used to identify yourself on the Tool. This need not be your real name. It also need not be the same as
  your Wikipedia username, however, we do also collect your Wikipedia username and associate it with your Tool username
  (see below).
- A password used to log in to the Tool. To protect your information, your password is salted and hashed using the
  `bcrypt` algorithm before being stored in the Tool's database. **Please use a unique password. Do not use a password
  that you use on any other site, and especially do not use the same password as used on any other Wikimedia project.**
- An email address used to contact you about your account, to send you notifications about your account, and to reset
  your password if you forget it.
- Your Wikipedia username. We require you to have a Wikipedia account in good standing in order to use the Tool, and
  you will need to allow the Tool to use OAuth to connect your account to verify your on-wiki identity. We also use
  OAuth to allow the Tool to automatically create accounts on your behalf from within the Tool, instead of requiring you
  to manually create them on-wiki. We will also check that your Wikipedia username appears on the list of users who have
  signed the [Wikimedia Foundation Confidentiality Agreement for Nonpublic Information][wmf-confidentiality-agreement].

Your email address is kept private and is only visible to Administrators and the Tool Roots. Your email address is never
shared with third parties or sold. Your password is likewise never shared or sold, and is indeed hashed so that it
cannot be read by anyone, including the Tool Roots.

However, please be advised that as access to the Tool is considered a high-trust position, **all other information given
here is considered public information** and is visible to all users, even non-Account Creators, in the interest of
transparency and accountability. This includes your Tool username, your Wikipedia username, and some of your activity on
the Tool, such as a list of all the account requests you have either created or closed. Examples of this public record
can be found at [the Tool's user list][acc-users]. Accounts you create through the Tool will also be publicly listed as
created by your Wikipedia username in the public [user creation log on Wikipedia][enwiki-user-creation]. Likewise, while
your Tool username and Wikipedia username need not be the same, please note that they will _both_ be visible and will be
tied to each other on the Tool, as well as both tied to your activity using the Tool.

While Account Creators' accounts in the Tool may be suspended to block their access to the Tool, they are never and
cannot be deleted in order to preserve logs and auditing data, again in the interest of transparency and accountability.

Note that there are some locations in the Tool where Account Creators may provide additional information that is shown
to the public, such as their email signature which is included in email notifications to Requesters. These locations are
marked within the Tool and Account Creators are responsible for ensuring they do not share any information they do not
wish to share. For example, it is not required that you use your real name in your Tool username or as your email
signature, but if you do, you are consenting to making it visible to the public.

**Account Creators are required to adhere to the [Wikimedia Cloud Services End User Terms of Use][wmcs-tou-users].**

## Disclaimers
Wikimedia Cloud Services (WMCS) is a project run by Wikimedia Foundation staff as well as trusted volunteers from the
community. The WMCS servers and infrastructure operate as a shared cloud, and as a result, data collected by the Tool
may also be accessible to the Wikimedia Foundation, its agents, and its staff; volunteer WMCS administrators; or other
WMCS developers in the course of their normal duties.

WMCS is hosted and operated in the United States. By using English Wikipedia Account Creation Assistance, you
acknowledge and understand that collection, use, storage, and other processing of your information (personal or
otherwise) as outlined in this Privacy Statement will take place in the United States. You understand that your
information also may be transferred to other countries, and that the United States and such other countries may have
different or less stringent data protection laws than your country. Furthermore, you acknowledge that your Personal
Information will be governed by this Privacy Statement, rather than the Wikimedia Foundation's Privacy Policy.

## History
For a history of changes to this Privacy Statement, please refer to the [GitHub commit
history][privacy-statement-history].

[wmcs-tou-devs]: https://wikitech.wikimedia.org/wiki/Wikitech:Cloud_Services_Terms_of_use
[enwiki-admins]: https://en.wikipedia.org/wiki/Wikipedia:Administrators
[enwiki-cus]: https://en.wikipedia.org/wiki/Wikipedia:CheckUser
[meta-stewards]: https://meta.wikimedia.org/wiki/Stewards
[acc-users]: https://accounts.wmflabs.org/internal.php/statistics/users
[wmf-confidentiality-agreement]: https://foundation.wikimedia.org/wiki/Legal:Confidentiality_agreement_for_nonpublic_information
[github-waca]: https://github.com/enwikipedia-acc/waca
[enwiki-user-creation]: https://en.wikipedia.org/w/index.php?title=Special:Log&type=newusers
[enwiki-upol]: https://en.wikipedia.org/wiki/Wikipedia:Username_policy
[wmcs-tou-users]: https://wikitech.wikimedia.org/wiki/Wikitech:Cloud_Services_End_User_Terms_of_use
[enwiki-ip-address]: https://en.wikipedia.org/wiki/IP_address
[enwiki-user-agent]: https://en.wikipedia.org/wiki/User-Agent_header
[enwiki-client-hints]: https://en.wikipedia.org/wiki/HTTP_Client_Hints
[wmf-privacy-policy]: https://foundation.wikimedia.org/wiki/Policy:Privacy_policy
[enwiki-upol-real-names]: https://en.wikipedia.org/wiki/Wikipedia:Username_policy#Real_names
[privacy-statement-history]: https://github.com/enwikipedia-acc/compliance/commits/main/privacy-statement.md
