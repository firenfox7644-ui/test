Following are the observation which are made. I need to make the single power point slide which is required to be shared with CEO of the Indigo. I am sharing the requirement from my manager in quotes” please help create a very short to the point single slide with Apryse, Redhat, and in house offerings. Feasibility, concerns and our recommended way forward given the time constraints. I will present it during my weekly and get a good ahead to be shared with Rahul or Procurement. ”
Apryse	Redhat	InHouse
Using the ITax5 from very long time.	New product, does not have prior experience of creating the ITax5 like technology	Would required time, code changes are required. But will take cosideratble to test and with multiple app

Server base pdf generator with proven 100% in pdf generations at the server side	Redhat using the indigo exiting microservices, what they are doing is web browser base ( UI) base conversion to PDF	Rajesh is exploring the options to built it in house doing POC. But there is no certainty as to the successful completion of project is not sure
Existing used. No deployment time required	New product for the redhat too. The whole process would take around 4-5 months to complete	1-2 month with no certainty of the successes of the product
Highly sensitive for customer. As timely receipts of boarding pass and GSt invoices are a must.
Any error or failure would result in P1 incident. Also effect the brand image of indigo	Considering the sensitivity of the product in the indigo eco system. New entrant with no prior experience on the same use case is not worth.	Since only 2.5 months are left for the license expiry. Developing a server side application, which might have multiple effects on the others pdf operations, should not be given the priority
Apryse SDK (WebViewer & Editor) indigo does not need this. 		
If we use only itext5, this will almost reduce the 50% billing currently we are pying to the apryse		

Additionally for you knowledge and reference, I am attaching the email conversation as received from the apryse team.

A. iText 5 Enterprise Subscription

[1] What additional capabilities are included as part of the iText 5 Enterprise subscription beyond the Core functionality?

Many of the use cases discussed during the workshop are supported through the current iText 5 entitlement, including:

•	Template (HTML)-driven generation of boarding passes, itineraries, invoices, and other travel documents
•	Document merging and assembly
•	Barcode and QR code generation
•	Watermarking and document security
•	PDF/A generation for archiving
•	Digital signatures
•	Multilingual document generation

[2] Are the Enterprise features bundled together, or can individual components/services be licensed separately?

The “Enterprise” designation primarily refers to the licensing model under the agreement rather than separate feature bundles.

Based on our understanding of the current contract, IndiGo has an enterprise entitlement with unlimited document processing. However, usage remains subject to the license scope and restrictions defined within the agreement.

[3] Which Enterprise capabilities are typically adopted by airline or large enterprise customers?

The use cases listed in your email are common enterprise and airline workflows, including:

•	Boarding pass and itinerary generation
•	GST invoice generation
•	PDF optimizations for efficient transfer from server to mobile devices and vice versa
•	Document assembly and packaging
•	Barcode and QR code generation
•	Digital signatures and approval workflows
•	PDF/A archiving
•	Security controls and document protection
•	Multilingual document generation

[4] Based on our existing usage patterns, what additional use cases could be enabled without requiring any additional licensing?

Based on the information shared to date, many of the use cases listed above could potentially be supported within the existing entitlement.

The key next step is to understand which applications are currently leveraging iText and whether there are additional internal use cases beyond the boarding pass and GST invoice workflows already discussed.

—————————————————

B. Apryse SDK (WebViewer & Editor)

[1] A detailed overview of the capabilities available under the Apryse SDK (WebViewer & Editor) - Overview of WebViewer's JavaScript Library | Apryse documentation

As covered during the workshop and capability deck, the current entitlement includes capabilities such as:

•	Document viewing and annotation
•	Editing and page manipulation
•	Search and extraction
•	Form creation and digital signatures
•	Redaction
•	Security and access controls
•	Accessibility support
•	Archive and PDF/A workflows
•	Document comparison
•	Office document workflows and conversion
•	HTML-to-PDF workflows
•	Collaboration and document review experiences

[2] Whether this SDK is independent of iText or complements/enhances iText-based implementations

The two products are independent but are frequently used together.
•	iText is typically used for server-side document generation and processing.
•	WebViewer is typically used for document viewing, review, collaboration, annotation, signing, and user-facing document workflows within web and mobile applications.

[3] The typical enterprise and airline industry use cases supported by this SDK

Examples discussed during the workshop include:
•	Passenger document review workflows
•	Boarding pass and travel document viewing
•	Digital approval workflows
•	Internal collaboration and annotation
•	Document comparison and audit workflows
•	Secure document access across web and mobile applications
•	Form-based document workflows
•	Digital signature workflows

[4] The document workflows, editing, annotation, collaboration, conversion, form handling, and other capabilities that can be leveraged under our current entitlement

These capabilities were covered as part of the capability workshop and accompanying deck shared with the team yesterday.

[5] Which use cases discussed during our previous interactions can be implemented using the existing license without additional commercial investment?

Based on our current understanding, many of the use cases discussed during the workshop could potentially be supported under the existing entitlement. Generally, WebViewer is perfect for document viewing and manipulation with custom security handler in mobile and web applications.

Also, many airlines uses WebViewer for their internal review workflow as discussed yesterday i.e. WebViewer empowers collaboration of document workflow (i.e. integration with outreach, sharepoint, etc, end-to-end document workflow will be in happening in one place). You do not have to toggle between applications to view different types of documents and remove the requirement on third party services such as docusign just to enable approval chain.

Webviewer can also power AI driven document experiences such as allowing users to ask/ prompt contextual questions about the content of a loaded document within the webviewer instance. For this, you may visit our github page for a quick look and also a sample code implementation: https://github.com/ApryseSDK/webviewer-samples/tree/main/webviewer-ask-ai.

To validate this accurately, we would first need visibility into the applications currently utilizing iText and WebViewer, as well as any additional applications that may be planned for future adoption.

Separately, as mentioned during our discussions, both the iText and Apryse WebViewer agreements include entitlement scope restrictions relating to the number of licensed applications (Enterprise License Products). The current restriction is up to 5 Enterprise License Products. We would therefore recommend identifying all current applications leveraging these technologies so we can jointly confirm alignment with the existing agreement.

—————————————————

C. Understanding Broader Adoption Opportunities across IndiGo

Given the objective of identifying additional adoption opportunities across IndiGo, it would be helpful if you could introduce us to the relevant application owners, business stakeholders, or teams responsible for document-centric workflows beyond the currently identified boarding pass and GST invoice use cases.

This would allow us to:
•	Understand existing document workflows across the organization
•	Validate current usage against the licensed application scope
•	Identify additional use cases that may already be supported under the existing entitlement
•	Help maximize adoption and value realization from the current investment

We would be happy to conduct additional workflow review sessions with the relevant teams as needed
