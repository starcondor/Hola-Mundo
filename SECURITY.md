# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | ✔️ |
| 5.0.x   | :x:                |
| 4.0.x   | 🔲 |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.

## Security policy: Mandatory code review


### **Create a branch for new features or fixes**

| Command | Description |
|-|-|
| git checkout | Branches available |
| git checkout *name* | Assigning a name for the branch |

### **Branch updates**

| Command | Description |
|-|-|
| git add . | Add all content to your branch. |
| git commit -m "Change description" | Specify the fix or change set. |

### Revision de la rama a evaluar

The review may take up to 3 business days to be verified and receive a response, in addition to having 4 more days to correct the changes or the branch will be discarded.

> [!NOTE]
> If your Pull Request is not approved after a reasonable amount of time, you can ask for feedback from reviewers or other team members. Avoid performing direct merges into the main branch without review.
This is just a basic example and you can adapt it to your team's specific needs. You may want to consider other security policies, such as setting up GitHub Actions workflows for security scanning and automated testing, before allowing the merge.

