# **External Attack Surface Assessment (Passive OSINT)**

Using passive OSINT tools like Shodan, I identified 3 exposed services affecting an educational institution without sending any active traffic to their network.

By reviewing publicly indexed banners and metadata, I filtered out standard public services and focused on ports exposing sensitive infrastructure. This led to 3 findings, two of which carried high risk, as an attacker exploiting them could gain unauthorized initial access, move laterally across the network, and potentially cause data leaks.

As a result of my analysis, I submitted a responsible disclosure report to the institution's security team detailing the exposures, their potential impact, and recommended firewall and configuration remediations.
