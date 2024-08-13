# OWASP Top 10 Exploitation Project in bWAPP
<!-- hide -->

> By [@rosinni](https://github.com/rosinni) and [other contributors](https://github.com/breatheco-de/owasp-top-10-on-bwapp/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

*Estas instrucciones estan [disponibles en español](https://github.com/breatheco-de/owasp-top-10-on-bwapp/blob/main/README.es.md)*

### Before you start...

> We need you! These exercises are built and maintained in collaboration with contributors such as yourself. If you find any bugs or misspellings please contribute and/or report them.
<!-- endhide -->

## 🌱 How to Start This Project?

In this activity, we will work with the beebox virtual machine, which contains bWAPP, to exploit vulnerabilities from the [OWASP Top 10](https://owasp.org/www-project-top-ten/). Below is a detailed example of how to exploit the **Security Misconfiguration (A05:2021)** vulnerability. Students will need to apply the same steps to the other vulnerabilities in the OWASP Top 10.

## 📝 Instructions

* Open this URL and fork the following repository: https://github.com/breatheco-de/owasp-top-10-on-bwapp

![fork button](https://github.com/4GeeksAcademy/4GeeksAcademy/blob/master/site/src/static/fork_button.png?raw=true)

A new repository will be created in your account.

* Clone this newly forked repository using Git to download it to your local machine.
* Once you have cloned it, follow the steps below to the end.

Let's get started! 🤓

### Step 1: Initial Setup

- [ ] Start the Virtual Machine.
- [ ] Access the bWAPP web interface from your browser using the beebox machine's IP address.

- [ ] **Log in to bWAPP**:

```bash
    - Usuario: bee
    - Contraseña: bug
```
 
- [ ] **Select the OWASP Top 10**. In the bWAPP menu, select "OWASP Top 10" from the dropdown list to view the available vulnerabilities.

 ### Step 2: Vulnerability Exploration

- **Review of Available Vulnerabilities**: Explore the different vulnerabilities from the OWASP Top 10 listed in bWAPP.
- [ ] Select **Security Misconfiguration (A05:2021)** for the guided activity.

## Step 3: Exploitation of "Security Misconfiguration (A05:2021)"

> 💡 This step is a detailed example of how to exploit one of the vulnerabilities from the OWASP Top 10. Students should follow these steps as a guide for the other vulnerabilities.

1. **Understanding the Vulnerability**:
    - **Security Misconfiguration** occurs when a system is not properly configured, which can lead to the exposure of sensitive settings, enabled insecure services, among others.

2. **Enumeration and Reconnaissance**
    - Use tools like **Nmap** to, for example, identify open ports.  
    `Example: nmap -sS -p- [IP_of_beebox]`
    - Scan the beebox machine to discover insecure default configurations and exposed services that might be misconfigured.

3. **Exploitation of the Vulnerability**
    - Once you have identified an insecure configuration (such as an unnecessarily open port), try to access it using default or no credentials.
    - In bWAPP, use the available functionality under "Security Misconfiguration" to test how these configurations can be manipulated to compromise the system's security.

4. **Documentation of the Process**
    - Document each step taken: from the identification of the insecure configuration, scanning and exploitation, to the results obtained.
    - Include screenshots and clear descriptions.

5. **Mitigation Proposal**
    - Describe how to fix the identified insecure configuration. For example, securing ports, disabling unnecessary services, or applying patches.


### Step 4: Apply Other Vulnerabilities from OWASP Top 10

- [ ] **Repeat the Process**:
    - Follow the same detailed steps outlined previously for each of the remaining vulnerabilities in the OWASP Top 10.
    - **It is important that you apply the pentesting techniques learned in previous weeks**, ensuring that you complete the scanning, identification, exploitation, and documentation process for each vulnerability.

### Step 5: Final Documentation

- [ ] **Prepare a Structured Report** that includes:
   - **Introduction**: General description of the exercise.
   - **Explored Vulnerabilities**: Details of each of the OWASP Top 10 vulnerabilities that have been exploited.
   - **Exploitation Methods**: Description of the techniques used to exploit each vulnerability.
   - **Prevention and Mitigation Proposals**: Solutions to prevent or fix each identified vulnerability.
   - **Conclusion**: Reflection on the process and the importance of secure configuration in web environments.

#### ⚠ Important!

- Ensure that each step follows the basic principles of pentesting: reconnaissance, scanning, enumeration, exploitation, and mitigation.
- When documenting the steps, include all possible details to ensure the final report reflects a comprehensive analysis.

## 🚛 How to Deliver This Project?

- In the root of the forked project, upload the report in `.pdf` format with the name `pentesting-report-OWASP-top10.pdf`. 

<!-- hide -->
## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Rosinni Rodríguez (rosinni)](https://github.com/rosinni) contribution: (build-tutorial) ✅, (documentation) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribution: (bug reports) 🐛

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind are welcome!