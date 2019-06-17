# Governance

The Paladin Project's mission is to provide an open, non-commercial ecosystem for the free sharing of ideas. We promote data portability, giving users ultimate control over their own social profile. This document outlines the basic organizational structure of the Paladin Project, serving as a reference for how decisions will be made.

## Structure

### Software

The Paladin Project maintains a collection of open source software projects. The key components of the system are:

* **Paladin Desktop:** A desktop application to create Paladin profiles, post status updates, and manage servers. This is the main user interface -- note that it is a desktop application, which grants the end user direct control over their data, rather than someone else's web service.
* **Paladin Server:** A web server to host end users' paladin profiles and facilitate user-to-user communication. It does not own the user's data, only makes it available to the network.
* **Paladin Registry:** A web server to host a public index of paladin servers in the network.

These software projects are supported by a number of important libraries; every project under the Github `paladin-privacy` organization is considered a component of the Paladin Project software collection. 

These software components are entirely open source and non-commercial. The code is owned by the individual contributors who wrote it. It is however licensed under the GNU GPL Public License, version 3. This license makes the Paladin Project's code available to everyone, while ensuring that it cannot be used in private, closed-source projects that may be commercial in nature.

We seek to create a free, open, and public ecosystem. Anyone may fork our software at any time to make their own changes and improvements, so long as that is done under the terms of the GPL license. This is a deliberate check on our own power as the Paladin Project -- if we become misguided, then fork our code and create something that isn't.

### Services

While our code is made available for free through Github for anyone to download and use, for the project to be successful we also need to host free and public Paladin servers for the general public to use, without having to set up their own webserver unless they want to. It is our goal to launch and maintain several public web services, using the open source software that we have developed. These include:

* **paladinprivacy.com** A website promoting the Paladin Project and its ecosystem.
* **paladin.social** A public Paladin server for anyone to use.
* **paladin.directory** A public Paladin registry to serve as a directory of publicly available paladin servers.

It is our commitment to keep the core infrastructure of our ecosystem noncommercial, and we expect our community to hold us to this through fair and free competition. These services will be maintained solely by donations, and operated by Futurspace.com LLC (which is a Washington limited liability company owned by the project's founders). We currently do not have the resources to manage a non-profit foundation, but it is our commitment to pursue that as a means of holding ourselves accountable to our commitments of non-profit governance, should the scale of the Paladin project grow to justify that kind of formal structure.

### Team

The Paladin Project will be a benevolent dictatorial anarchy managed by its founders. We will make the final technical decisions for this project, but our software will be designed to freely interoperate with any programs that are compatible with its APIs.

Our current team members include:

* **Matt E:** A full stack software and UX engineer in Seattle, Washington. 

## Policy

**Note:** The purpose of these sections is to explain our policies to Paladin users and contributors. For an official response to any law enforcement or legal inquiries, please contact us at legal@futurspace.com

The Paladin Project and Futurspace.com LLC (which hosts the ecosystem's core services) share a commitment to promote freedom of expression online. We are not the arbiters of truth. We are programmers, and recognize that an open exchange of ideas is crucial to the survival of democracy across the globe. 

### Law Enforcement & Warrants

We consider our project's core team and services to fall under the jurisdiction of the state of Washington in the United States of America. We will comply with all legal requirements in this jurisdiction to the fullest extent that we can under the law. 

This means that if we receive a valid, court-issued warrant to turn over your data to authorities, we will do so as required by law. Note that Paladin supports various forms of encryption. Private Paladin profile fields and fields set to share to friends only are encrypted in such a way that no server, including the Paladin Project team and Futurspace.com LLC, has the ability to read that data. Only users who you share that data with can read it. Therefore we will turn over the encrypted version of that data as required, and any keys that are in our possession. It will be of course physically impossible for us to turn over any data unless it is actually in our physical possession, such as the private keys for this data or the unencrypted text.

We will not comply with any requests for information unless we are required to by law. We will not make any undesired changes to our software except required by law.

### Acceptable Content

The Paladin Project is neither an arbiter of truth nor a moderator of public discourse. The Paladin Project is a team of programmers who provide software and the core elements of an ecosystem. We are not in a position to decide what is civil or acceptable discourse at the societal level, and it is in our firm opinion that no centralized source of power can be trusted with that authority.

However, it is necessary for society to have law. We will remove content if, and only if one of the following is true:

* It promotes terrorism or other violent harm
* It violates copyright, AND a valid Digital Millennium Copyright Act notice is received from the copyright holder
* We are legally required to remove that content
* It violates the terms of service of one of our hosting providers (namely Amazon Web Services)
* Not removing that content would incur legal liability on our part (example: content that clearly meets the legal definition of libel).
* It exposes any specific, identifiable human being to real world violent harm through methods such as "doxing."

We have architected our software to make it difficult for individual messages to be removed in an attempt to prevent subtle influences in what users see in their feeds. For this reason, our policy is all or nothing. If we think your content is violating these policies, then you will be blocked from core Paladin services in order to meet our legal requirements.

Note that these restrictions apply to services in the Paladin ecosystem; we may have more specific standards for professional conduct when contributing to our software projects.


