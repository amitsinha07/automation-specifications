# ONDC:TRV11 2.0.1 — Overview

## Summary

ONDC:TRV11 is a standardized protocol for buying and selling intra-city public transportation tickets—buses and metros—through an open digital network. It enables passengers to book tickets from any transit operator using any connected buyer app, and allows operators to reach customers without building their own consumer interfaces. This domain creates a unified marketplace for urban mobility ticketing.

## Sector & Purpose

The urban mobility sector covers public transportation within cities. The problem ONDC:TRV11 solves is marketplace fragmentation: passengers traditionally must download separate apps for buses, metros, and different operators in each city. Transit operators, meanwhile, must maintain expensive consumer-facing platforms or rely on aggregators. ONDC:TRV11 creates a standard protocol that lets any buyer app access any operator's inventory, and any operator reach all buyers through the network—similar to how flight booking aggregators work, but for daily urban transit.

## Real-World Actors

The participants in ONDC:TRV11 transactions are:
- **Passengers**: individuals traveling within a city on buses or metros, seeking quick, convenient ticket booking
- **Transit operators**: public or private organizations running bus services or metro networks in a city (e.g., Delhi Metro, state bus services)
- **Buyer apps**: consumer-facing digital platforms where passengers search and purchase tickets (often part of larger mobility or fintech apps)

## Use Cases

- Book a single metro ride from one station to another
- Book a single bus trip within a city from one stop to another
- Purchase a monthly or unlimited-travel pass for buses or metros
- Cancel a ticket before travel and receive a refund
- Change your destination station or stop after booking but before departure
- Search transit options by station names or codes
- Resolve refund disputes or service complaints through a standardized process

## Key Concepts

- **Intra-city travel**: movement within a single urban area (as opposed to intercity long-distance routes like Delhi to Mumbai)
- **Transit operator**: the organization providing the service—running buses, metros, or other urban transit
- **Buyer app**: the digital storefront through which passengers search and book; not the operator's app, but an independent marketplace app
- **Ticket confirmation**: the protocol moment when a passenger's seat or space is reserved and locked in, generating a bookable ticket
- **Issue Grievance Management (IGM)**: a standardized process for handling cancellations, refund disputes, and service complaints across the network

## Example Scenario

A passenger in Delhi needs a metro ticket from station A to station B. She opens a buyer app (say, a fintech app or mobility aggregator) connected to the ONDC:TRV11 network, searches for available trains, selects one, and confirms her booking. The app communicates with the Delhi Metro operator through ONDC:TRV11; the operator reserves her ticket and sends a confirmation back. She receives her ticket in the app.

Later, she decides to get off at a closer station instead. She opens the app and requests an end-stop change. The operator updates her ticket.

In a second scenario, a commuter in another city needs a bus ticket from stop A to stop D. Using a different buyer app, he searches available routes and books with a bus operator—again, all through ONDC:TRV11. If he cancels before departure, he receives a refund through the same app.

If either passenger encounters a problem—a delayed refund, an incorrectly applied cancellation fee, or a seat issue—ONDC:TRV11 provides an Issue Grievance Management process to resolve it fairly without getting trapped in the operator's customer service system.

The key point: whether booking a metro in Delhi or a bus in another city, using any buyer app, both passengers use the same protocol and get a consistent experience. Operators reach all these passengers without building separate consumer channels.
