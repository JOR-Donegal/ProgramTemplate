# Week 4
The most common Authentication, Authorization and Accounting (AAA) infrastructure we find in modern enterprise and data centres is Microsoft's Active Directory (AD). It's useful for centralizing information in an SME, but it's essential for any infrastructure that needs to scale. Once the site goes beyond a trivial size, its security information becomes unmanageable unless we centralize it. This week we are going to work on some of the theory and terminology behind having a local AD infrastructure.

In practical exercises this week, build the core services for a basic SME site using Active Directory. This should have two domain controllers, each having redundant AD, DNS, DHCP. One of the controllers should be set to synchronize time to a source of NTP. Plan the site as if it has no Internet connectivity.

## Actions
1. Read through my theory material on [Active Directory](https://johnoraw.gitbook.io/active-directory-1/)
2. Build Authentication, Authorization and Accounting (AAA) infrastructure for an SME site, using scripts and configuration files where posible.