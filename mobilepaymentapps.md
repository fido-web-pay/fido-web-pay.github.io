## FIDO in a world owned by proprietary mobile banking and payment apps
It is a fact that banks spend millions of dollars each year on proprietary
mobile banking solutions.

These applications typically have multiple uses including payment support.
The more advanced of these solutions cover a wide range of payment scenarios,
including:
- On-line (Web)
- PoS (Point of Sale)
- P2P (Person to Person)
- Invoice payments

In addition to that, most of these solutions are also used for **login**
when the user is on a "PC" running a Web version of the on-line bank
as well as supporting **3D Secure**.  

**Open Banking** introduced yet another function for mobile banking applications:
Strong Customer Authentication (**SCA**).
Current Open Banking APIs are written in such a way that they do not depend
on any specific SCA solution.

_That is, it is not entirely obvious why banks would switch to FIDO
based solutions_. However, there is one big difference between
banking and payments: while banking systems may be pretty bank-specific,
payment solutions targeting external entities like merchants make
proprietary systems much less attractive.  History shows that only giants
like PayPal, Amazon, and AliPay can realistically succeed with such endeavors.

<table><tr><td><i>That most digital payments in the physical world
  are based on an internationally accepted standard, <b>EMV</b>, shows the
  importance of standards</i></td></tr></table>

## On-line payments - No (<i>generally accepted</i>) standards
However, in the on-line world things are more complicated because
merchants are facing a multitude of quite different payment options.
Although mobile banking and "wallet" applications enjoy a high
acceptance in many countries, _these systems still tend to be
regional_.  While Apple & Google Pay are not constrained by national
borders they 1) are not interoperable 2) only support card networks.
## FIDO come to rescue?
Banks are understandably highly reluctant taking on yet another system that "does the same thing".
There are though a few things that _could_ change the picture:
- Merchants (including their customers), are probably interested in _any_
standard payment solution if it is good enough
- Account-2-account schemes like SEPA instant, currently lack support for consumer 
to merchant payments (C2B).  Not only on-line, but in the physical world as well 

This is the primary rationale for [FIDO Web Pay](https://fido-web-pay.github.io/) (FWP),
which is a combination of a Browser-resident (built-in) payment application, FIDO, and an enhanced version of EMV.
Due to its EMV origin, FWP lends itself to PoS scenarios as well, albeit using QR code invocation.

<table><tr><td><i>That banks would drop their mobile banking applications (or
  rebuild them to use FIDO) seems
 rather unlikely to happen anytime soon.
Supporting a standardized (and popular) payment solution may prove to be a more
realistic way to get a foothold in the banking community</i></td></tr></table>

Note: whatever payment system you have, it will take considerable time and 
substantial marketing to _hopefully_ reach the critical mass required.

Version: 2021-03-25
