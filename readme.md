# Project Specification

## Objective

A local company is planning to set up a bike share programme in the city of Edinburgh. In order to ensure
the efficiency of its operations and guarantee a high-quality customer experience, the company has decided
to outfit the programme with a new mobile reservation system that connects customers with bikes,
together with a system that enables its operational control centre to monitor and make changes to the
overall state of the bike share system (e.g., track the location of bikes, replace defective bikes, order bikes to
be redistributed to new locations in the city, etc.), and for managers to review usage reports and statistics.
The company is eager to try out new technology and offer new features that aren’t currently available in
bike share programmes in other cities. The system will be deployed throughout the city and, depending on
its success, may be deployed in other cities where the company operates.

You are a small software company who have come up with an idea that meets the needs of the company
running the bike share programme. In order to properly demonstrate your idea, you need to create a
functioning end-to-end prototype and demonstrate it with appropriate data. Your product is meant to
provide an efficient and flexible interface for customers to reserve bikes; for operators to assess the state of
the system and make changes if necessary; and for managers to view usage reports. Each set of users must
be able to interact with the product in a way that best provides them with the tools that are appropriate for
their specific needs.

## Scope

Think who your users/stakeholders are and develop a set of use cases. The desired solution is to be scalable
and flexible enough to support the different types of users (customers, operators, and managers) who may
each require different types of information to be presented to them in a different form. Consider this in
your system design. For your demonstration, you will need to simulate bike share locations across the city of
Edinburgh (at least 10 locations, or however many is needed to really show off your product’s functionality).

## Outline Requirements

Use some prioritisation technique (e.g., MoSCoW) to enable a common understanding to be reached on the
relative importance placed on the delivery of each requirement. Requirements are purposely
underspecified in this document and it will be up to your team to specify a comprehensive set of
requirements that enables you to design, implement, and deliver your proposed system. Outline
requirements include:

- [ ] Create a system that enables customers to reserve bikes at particular locations in the city for
particular times. Reservations can be cancelled or changed if necessary through the same system.

You can reserve a bike from a location. The number of bikes cannot go below the number of reservations to be picked up in the next 24hrs. Any deficeit is covered by the man in a van. Fixed fee = daily fee.

- [ ] Create a control system that enables operators to perform common tasks like tracking the location
of bikes, replacing defective bikes, and redistributing bikes to different locations in the city.

Allow the option to give a discount to drop offs at particular locations. Otherwise the man with the van can move from location to location, or collect stray bikes.

- [ ] In addition to the basic system, the company will deploy a bespoke service where specialised bikes
(e.g., road bikes, tandems, etc.) and a limited amount of bike gear (e.g., helmets, bike pumps,
panniers, etc.) can be reserved at particular locations in the city.

Specific locations with special types of bikes/equipment. Rental is more expensive, and must return to the same location.

- [ ] The system must be robust to changes in customer orders (e.g., a change in pickup time) and inform customers about changes to the state of the bike share system that affect existing reservations (e.g. bikes that no longer available).

A cancelled or moved reservation will open up the bike again. Keep the reservation fee if cancelled < 24 hrs.

- [ ] The company is interested in new and useful features that (ideally) aren’t available in other bike share programmes.

Complex pricing system with incentives and big data.

- [ ] Create a management system that enables managers to view useful statistics about bike usage (e.g.,
number of reservations, location usage, etc.).
- [ ] Customers should be able to use the system to report problems or faults with their bikes.
- [ ] The system must have a way to track bike returns.
- [ ] Users must be able to quickly interact with the various systems and easily manipulate the relevant information that is presented in each case.
- [ ] Key pieces of information should be distilled visually and broken down into chunks that are appropriate for a particular user.
- [ ] The solution should be tested and be fully responsive across all the common web browsers (e.g., Google Chrome, Mozilla Firefox, Apple Safari, and Microsoft Edge), on all mobile and tablet devices
(e.g., Android, iOS, or Windows), while providing a good user experience.
- [ ] Daily summary reports for individual locations and the overall system would be useful.

## Additional Clarifications

Some additional clarifications about the task:

- [ ] Branding and system names are to be determined by the team. Note that the company is only your
first customer so the branding should appeal to all potential customers (e.g., in other cities).
- [ ] Your preference should be to use open source software, themes, and style guides.
- [ ] Feel free to use any other resource available to you but make sure you acknowledge any copyright.

## Deadlines and assessment

Complete information about deadlines and assessment criteria can be found on the [Group Project website](http://www.macs.hw.ac.uk/~rpp6/teaching/GroupProject/).


