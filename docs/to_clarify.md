## Questions

### User Stories

1. Stated under "Context" that "hotels... have tried different digital check-in solutions to limited success". What are some of these solutions and in which aspects are they lacking? Can we physically or digitally try out these solutions? This would help us in learning from past attempts and to come up with a better solution.

1. Can we arrange a timeslot for my team to physically or digitally go through the current check-in/out process? This will help us have a better understanding of the pain points experienced when using the existing solution.

1. Stated under the section "Possible Use Cases" that the solution should "enhance back-end operational capabilities and business intelligence by integrating with existing solutions and databases", which will be used to "create accurate guest profiles and provide personalized and targeted guest experiences".

    a. Is the inability problem simply due to lack of integration across systems, and so the solution would "enhance back-end operational capabilities and business intelligence" by simply "integrating with existing solutions and databases"?

    b. Does the solution contain capabilities to "create accurate guest profiles", or is that out of the scope?

### Integration

1. Stated under the section "Possible Use Cases" that the solution should "integrat(e) with existing solutions and databases".

    a. What are the APIs (e.g. REST, SOAP, gRPC) used to communicate with these existing systems?

    b. Will documentation & assistance be provided if we face issues interfacing with these systems? For example, if we require additional API that is not yet implemented by an existing system, will we have to modify the existing codebase to implement the API that we need, or will someone be assisting us instead?

    c. On the same note, are there systems depending on the existing check-in/out system? If so, is the means of communication same as the answer to a.?

1. Stated under the section "Possible Use Cases" that the solution should "allow data transference capabilities, from room requests collected on the booking engine, to the check-in process till checkout". Does this mean that the "digital mobile check-in and check-out solution" is expected to do more than digitising the checking-in and checking-out processes; it has to integrate with other platforms to provide other additional services, beginning from the booking of hotel rooms till checkout?

### Security

1. Stated under the section "Problem Statement" that the solution must be "safe and secured to protect guests' privacy". What exactly does this requirement mean, for example, are there certain security standards that the solution must adhere to?

### Deliverable

1. Is there a sample proposal that we can reference? This will be helpful in guiding us on what we should include in our proposal and how to best structure it. If not, can we have a list of requirements that we must particularly address, perhaps for example, the tech stack of the solution?

### Check-in/out Questions, If Unanswered

1. Stated under the section "Possible Use Cases" that the solution should "begin their check-in journey before arrival and complete it upon arrival".

    What needs to be done during the digital checking-in process? Is there any of the hidden/back-end process must be adhered to provide a seamless and contact-less check-in process?

    b. Which part of the process can guests complete up to before arrival, and what else do they need to do to complete the check-in process upon arrival?

    c. On the same note, what needs to be done during the checking-out process?

1. Stated under the section "What Are We Looking For" that the solution should "verify travel and identification documents, booking documents, payment details, and make payment upon check-out, integrated with ICA (or other government stipulated system) for authentication and verification".

    a. Which government stipulated system is currently being used, and does the existing system provide API for our solution to communicate with it?

    b. Can we have several different samples of the above documents and the details of what are being verified for these documents?

1. Stated under the section "What Are We Looking For" that the solution should "streamline the back-end allocation of rooms by ensuring room requests are clearly accounted for on the back-end, to ensure rooms and amenities are available upon guest arrival". Is this currently being done, and if so, how is it being done?