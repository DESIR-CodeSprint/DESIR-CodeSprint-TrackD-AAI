# Track D - AAI: Securing Online Services in the DARIAH AAI using SAML/Shibboleth

In order to promote [DARIAH](https://www.dariah.eu/activities/projects-and-affiliations/desir/) tools, services, and initiative collaborations, DESIR organises a series dissemination events, one of them is the [code sprint](https://desircodesprint.sciencesconf.org/) event which will be held on 31th July - 2nd August 2018 in Berlin. As one of events that is organised by the DESIR project, the code sprint this year take *Bibliographical metadata: Citations and References* as the main subject. 

To support this theme, **track D** focuses on making online Web Services available to researchers using the DARIAH Authentication and Authorization Infrastructure (_AAI_). 

# DARIAH AAI at a glance
The DARIAH AAI enables researchers from [eduGAIN](https://technical.edugain.org/status) to access DARIAH services, by using the interoperable [SAML standard](https://www.oasis-open.org/committees/security/). Users can log in at their home institution, without the need to create accounts and remember passwords for the online services they want to access. Adding to this, the DARIAH AAI allows for central yet distributed management of group memberships. Thus DARIAH online services can base their authorization decisions on these memberships.

# Goal of this Workshop
This workshop will introduce the DARIAH AAI and enable its participants to install, configure and test the Shibboleth Service Provider (*SP*) to integrate with an online service. The main _goal_ is to make the participants familiar with the Shibboleth SP and how it integrates with their Web application. 

The workshop will of course also provide for 
* an introduction to SAML from an SP side, 
* recommendations for further open-source SP implementations besides Shibboleth
* a comparison with other AAI technologies like OAuth2 and OpenID Connect

# Agenda
We will be free to intermix theory parts and practical hands-on sessions during the workshop.

Theory:
* Single Sign-On (_SSO_) concepts for Web applications
* Identity Providers (_IdPs_) and Service Providers (_SPs_)
* Federations and eduGAIN
* Introduction to SSO using SAML
* Introduction to Shibboleth as a language-independent SP solution
* On top of SAML and eduGAIN: benefits of the DARIAH AAI
* Architecture of the DARIAH AAI IdP Proxy Solution
* Other SP implementations
* Other SSO technologies (OAuth2, OpenID Connect)

Hands-On:
* Install the Shibboleth SP on Linux
* Configuration against the DARIAH AAI Proxy IdP
* Vhosting / using logical SPs
* Initiating a session (active and passive protection)
* Authorization options: application-based, htaccess, XML-based
* Interaction with applications in various programming languages
* Using DARIAH AAI attributes for authorization
* Management of authorization groups using the DARIAH SelfService

# Preparing for the AAI Track
* Participants should bring their own notebooks, either 
.* with a Linux host OS, or
.* a Linux guest virtual machine on the notebook
.* or prepare a Linux server they can access remotely from their notebook
* You need root access on that machine
* Your machine should be configured such that you can resolve a URL like https://localhost/my-application.php, or https://127.0.0.1:2345/my-app.pl, or https://my-server.org/my-app.jsp from your desktop / Web browser.

It *is* certainly possible to use a Windows OS for installation of the Shibboleth SP. We can give hints as we go along for participants wishing to use Windows.

# Contact
For more information, please contact the presenter
- Martin Haase (martin.haase@daasi.de)
