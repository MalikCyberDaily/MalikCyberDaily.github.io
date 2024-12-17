---
layout: default
---

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Building a SOC + Honeynet in Azure (Live Traffic)
Built a Honeynet SOC in Microsoft Azure to capture and analyze live traffic. Using Microsoft Sentinel and KQL (Kusto Query Language), logs were aggregated into a Log Analytics Workspace to monitor security events, syslogs, and malicious activity. The environment was initially left insecure to attract attackers, resulting in over 1,700 malicious flows and multiple failed authentication attempts. After implementing NIST 800-53 security controls, including hardened NSGs, firewalls, and private endpoints, security incidents were reduced by 100%, showcasing effective hardening. This project demonstrates robust incident detection, monitoring, and hardening within a cloud-based SIEM environment.
[Link to Building a SOC+Honeynet in Azure(Live Traffic) Project](./https://github.com/MalikCyberDaily/Azure-Honeynet-SOC).


# Creating-Azure-Honeypot
In this project, two Azure virtual machines (Windows and Linux) were deployed and configured as a honeypot by disabling firewalls and creating NSG rules to allow all inbound connections. This setup intentionally exposed the environment to attract malicious traffic for analysis. The configuration serves as a foundational step to observe and analyze attacker behavior within an insecure cloud environment.
[Link to Creating Azure Honeypot Lab](./https://github.com/MalikCyberDaily/Creating-Azure-Honeypot/tree/main).


# AWS Cloud Cybersecurity Homelab Red/Blue Team
In this project, a Red/Blue Team Cybersecurity Homelab was built in AWS using a Virtual Private Cloud (VPC) with Kali Linux (attacker), Windows 10 (vulnerable client), and Ubuntu (security tools). Splunk was configured on the security tools VM to collect and analyze logs from the Windows machine via the Universal Forwarder, enabling security monitoring and event analysis. Additionally, Tenable Nessus was deployed on Ubuntu to perform vulnerability scanning. This environment facilitates Red Team attack simulations and Blue Team defense strategies, providing a controlled cloud-based lab for hands-on cybersecurity training.
[Link to AWS Cloud CyberSecurity Homelab Red/Blue Team](./https://github.com/MalikCyberDaily/CyberHomeLab/tree/main).

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
