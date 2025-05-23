# Samuel's Algorand-ticket-nft

AlgoEvents

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

AlgoEvents is a decentralized platform built on the Algorand blockchain to create, host, and attend events using NFTs as tickets. It ensures secure ticketing, fraud prevention, and seamless event participation via on-chain verification and wallet integration.

# Features
- Organizers can mint multiple tickets for an event as NFTs, simplifying bulk issuance.
- The create page now supports issuing Free Tickets, offering flexibility for different types of events.
- A new tab under host displays all events hosted by the user, streamlining access and management.
- The events route has been redesigned for a cleaner and more intuitive user experience.
- Tickets are signed with the private key of the issuer; at check-in, QR codes are scanned, payloads and signatures are decoded and verified with the public key to ensure ticket authenticity.
- The calendars page now displays all events the user is subscribed to or has tickets for.

# Upcoming Features
- Implementation of verification for NFT asset metadata and the creator’s address during ticket check-in.
- Event organizers will be able to mint and send certificates to participants after the event ends.
- Add map location integration on the create page to display where events will be held.
