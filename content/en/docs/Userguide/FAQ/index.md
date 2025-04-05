---
title: "SW360 User Frequently Asked Questions"
linkTitle: "FAQ"
weight: 21
---

##### 

---

### **What is SW360?**  
SW360 is an open-source software project licensed under EPL-2.0. It provides both a web application and a repository to collect, organize, and make available information about software components. SW360 serves as a central hub for managing software components, tracking licenses, security vulnerabilities, and enforcing compliance across the development process.

### **Who should use SW360?**  
SW360 is designed for organizations that use third-party software components in their projects. It’s especially useful for quality managers, software developers, legal teams, software architects, and R&D managers who need to ensure software compliance, manage component data, and track software vulnerabilities.

### **What problems does SW360 solve?**  
SW360 helps organizations with:
- Verifying third-party software compliance (license, security, export control, etc.)
- Managing software components and their qualities
- Providing visibility into the components used across projects and products
- Automating compliance processes such as legal, security (SBOM), and IP assessments

### **What are the core features of SW360?**  
Core features include:
- Component tracking and management
- License compliance management
- Security vulnerability tracking
- End-to-end compliance toolchain (including integration with tools like FOSSology)
- API access for seamless integration with DevOps tools



### **I'm having issues logging in. What should I check?**  
Verify that your credentials are correct and that your account has the appropriate access rights. Ensure your browser is not blocking cookies or session data, and check that your network connection is stable.

### **I can't log in to SW360. What's the issue?**  
Login issues may be caused by incorrect credentials, session timeouts, or browser settings blocking cookies. Verify your credentials and check your browser’s privacy settings.

### **SW360 is running slow. What can I do?**  
If SW360 is slow, try clearing your browser cache, ensuring a stable network connection, and checking server load. If the problem persists, contact your system administrator for further support.

### **I encountered an unexpected error while using SW360. How should I troubleshoot it?**  
Record the error message, check system logs, and refer to SW360 documentation or community forums for guidance. If unresolved, contact the SW360 support team for assistance.

### **How can I report a bug or request a feature in SW360?**  
You can submit bug reports and feature requests via the SW360 issue tracker or directly contact the support team.


### **Who should be listed as a Moderator?**  
Moderators are individuals who need to review changes made to specific items such as projects, components, or releases. They typically have higher access rights to review and approve changes. In SW360, moderators play a role similar to the "Software Clearing Site Representative."

### **Who should be listed as a Contributor?**  
Contributors are individuals who need to modify an item (e.g., project, component, release). These are typically people like software architects, developers, or other experts who are allowed to contribute to the project's data.

### **I have changed a project, component, release, or attachment, but SW360 does not show the changes?**  
If your changes require moderation, they will need to be approved by a Moderator. You can check the status of your submissions by going to the "My Task Submissions" section on the Home view.

### **What should I enter in the field 'Visibility'?**  
The "Visibility" field determines who can view a project. The default setting is "Everyone," meaning the project is visible to everyone within the organization. You can adjust visibility to control access based on the audience.

### **How can I change the 'Clearing State' of a release?**  
The clearing state changes based on the status of clearing reports. If no report is available, the state is "New." Once a clearing report is available, the state is "Clearing Report Available," and if approved, it is marked as "Approved."

### **I can't find a specific release inside my project. What can I do?**  
You can sort each column (e.g., by name, project origin, clearing state) to help locate specific releases more easily.

### **I can't delete my component called 'Tom's Test Component'.**  
Special characters like single or double quotes in component names can cause issues. Rename the component to remove special characters before trying to delete it.

### **What is the Copyleft Effect?**  

**Copyleft** effect is the reverse idea of **copyright**. Goal is that software licensed under such license is always free and can never get a privatised software asset. The user gets the freedom to run, copy, modify and distribute the software, but it is not possible to add any further restrictions. This implies that **modified software** must also be free and becomes available to the community.

### **Different Classification of the Open Source Licenses.**  

There are hundreds of OSS licenses, the following table will give a brief overview about the most common OSS licenses, the risks and the obligations that need to be fulfilled when using them:

| | License Class | License Name(s) | Risks | Obligations |
| --- | --- | --- | --- | --- |
| <span style="color:white;font-size:2em;">&#9899;</span> | **White Licenses** | MIT, BSD (except for BSD-4-Clause), BSL-1.0, CPOL-1.02, MsPL, zLib, Apache-1.1, Apache-2.0 (if no code changes are done) | **low risk** | Mostly standard obligations: display license text, display copyrights |
| <span style="color:yellow;font-size:2em;">&#9899;</span> | **Yellow Licenses** | CDDL-1.0, CPL-1.0, EPL-1.0, eCos License, MPL, NPL | **medium risk** - because of non-standard obligtions in some cases | Display license text; display copyrights; all changes of the component code must become OSS as well; possible license incompatibility with red licenses |
| <span style="color:red;font-size:2em;">&#9899;</span> | **Red Licenses** | GPL-2.0, GPL-3.0, LGPL-2.1, LGPL-3.0, AGPL | **check before use** some special obligation which might be not in line with your lans | Display license text; display copyrights; take care about copyleft effect - get in contact with your software clearing experts; all distributions must clearly state that (L)GPL license code is used |
| <span style="color:red;font-size:2em;">&#9899;</span> | **Red Licenses** | SleepyCat, Aladdin Free Public License; Berkeley DB licenses |  **really check before use**  because of nearly unlimited copy left effect | Before thinking about components licensed under these license, get in contact with your software licensing experts! |
