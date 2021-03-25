## FIDO in a world owned by proprietary mobile banking and payment apps
It is a fact that many banks spend millions of dollars each year on proprietary
mobile banking solutions.

These applications typically have multiple uses including payment support.
The more advanced of these solutions cover a wide range of payment scenarios,
including:
- On-line (Web)
- PoS (Point of Sale)
- P2P (Person to Person)
- Invoice payments

In addition to that, many of these solutions are also used for login
when the user is on a "PC" running a Web version of the on-line bank
as well as supporting 3D Secure.

_That is, it is not entirely obvious why banks would switch to FIDO
based solutions_. However, there is one big difference between
banking and payments: internal systems may be pretty bank-specific,
while payments targeting external entities like merchants make
proprietary systems much less attractive.  To reach massive adoption
of such systems is essentially only possible for giants like PayPal, Amazon, and AliPay.

<table><tr><td><i>That most payments in the physical world
are based on an internationally accepted standard, EMV, shows the
  importance of standards</i></td></tr></table>

## On-line payments - No standards
However, in the on-line world things are more complicated because
merchants are facing a multitude of payment options that also build
on quite different platforms.  Although the mobile banking applications
for payments are very popular in many countries, _they are still only working on
a national level_.  While Apple & Google Pay are not limited to national
borders they 1) are not identical 2) only support card networks.
## FIDO to rescue?
Banks are undoubtedly reluctant taking on yet another system that "does the same thing".
There are though a few things that could change the picture:
- Merchants (including their customers), are probably quite interested in having a standard solution
- The ability to support account-2-account payments like SEPA instant have so far
not happened in a big way with the proprietary solutions

This is the sole rationale for [FIDO Web Pay](https://fido-web-pay.github.io/)
which do not only leverage FIDO but EMV as well.

Note: whatever system you have it will take time and require substantial marketing to
_hopefully_ succeed.

Version: 2021-03-25
