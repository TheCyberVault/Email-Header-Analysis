## Suspicious Email Investigation

### Getting Started

📧 **The Odd Email**: So, you've got this email that's supposedly from Microsoft about a Defender product deal. But here's the catch - it's from a Gmail address (`microsoftsubscription4838246@gmail.com`). That's like someone claiming to be a gourmet chef but serving you instant noodles. Red flag, right?

### Dive Into the Detective Work

#### Task 1: Email Deep Dive

- **Your Mission**: Fire up a new tab and hit up [CentralOps.net](https://centralops.net). It's like the digital equivalent of checking someone's ID. Find the Email Dossier and get cracking.
- **What You Do**: Punch in `microsoftsubscription4838246@gmail.com` and let it rip.
- **What You're Looking For**: You're hoping to see if this email is legit or just digital junk mail. The results are your first clue.

![centralops](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/b9332e21-1433-438d-9ee4-b37d7e91032c)


#### Task 2: Reverse Lookup – Who Are You Really?

- **Your Mission**: Next stop, [That'sThem Reverse Email Lookup](https://thatsthem.com/reverse-email-lookup). It's like looking up a phone number in an old phone book, but for email.
- **What You Do**: Enter the mysterious email address and search.
- **What You're Looking For**: Ideally, you'd find a real person tied to this email. But if it comes back empty, that's another point for Team Suspicious.

![reverse lookup](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/9759aa95-a366-486c-b29c-7ebd4e43766a)


#### Task 3: Reputation Check – Are You Trustworthy?

- **Your Mission**: Time for a quick trip to [emailrep.io](https://emailrep.io). Think of it as checking someone's social credit score, but for their email habits.
- **What You Do**: Submit the email and see what the digital world thinks of it.
- **What You're Looking For**: Is this email the digital equivalent of a knight in shining armor or a sketchy character from a back alley? The rep score will tell.

![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/719a8033-3150-4485-bcbe-99f92852ac2e)


#### Task 4: Breach Check – Have You Been Around?

- **Your Mission**: Drop by [';--have i been pwned?](https://haveibeenpwned.com). It's like finding out if someone's been gossiping about you in places they shouldn't.
- **What You Do**: Type in the email and cross your fingers.
- **What You're Looking For**: You're hoping this email hasn't been caught up in any digital scandals. If it's clean, that's a good sign.

![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/4eaa4415-7775-49ae-9859-2e6dac818046)


#### Task 5: Header Analysis – Tracing the Digital Footsteps

- **Your Mission**: Head over to [MXToolbox](https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx) for some serious detective work. This is where you put on your digital detective hat and trace the email's journey.
- **What You Do**: Paste the email's header and analyze.

![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/89d5bb76-eab6-43b6-bddd-cbd62e50026d)
![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/ad9af1e4-effd-4ab2-8906-e5a813ccdc38)

- **What You're Looking For**: This is like mapping the email's road trip across the internet. Any weird detours or shady stops? That's what you need to note.

#### Task 6: WHOIS Lookup – Who's Behind the Curtain?

- **Your Mission**: Visit [whois.com/whois](https://whois.com/whois) for a bit of digital stalking (the legal kind, of course). You're looking up the domain found in the email's header.
- **What You Do**: Type in the domain and hit search.

![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/a451fce2-9f73-4c2b-8250-7aa58324d090)
![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/d8e1dbbb-d2b8-4e79-b0cb-9c42badb5e7a)


- **What You're Looking For**: This tells you who owns the domain. If it's someone reputable, great! If not, add it to the suspicion pile.

![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/076415ce-80af-4429-964d-a8f6ef4b9744)


#### Task 7: IP Deep Dive – Where in the World?

- **Your Mission**: Time for a geography lesson with [ARIN](https://arin.net). You're checking out the IP address from the email header to see where it really came from.
- **What You Do**: Enter the IP address 217.138.207.226 and start the search.
- **What You're Looking For**: This is like pinning the email's location on a giant digital map. Paris, France? Cool, but only if it makes sense.

![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/a3e8c761-e670-45a3-aaca-533c465770bb)


#### Task 8: Final Check – Pinpointing the Location

- **Your Mission**: Last stop, [IP2Location](https://ip2location.com). You're double-checking the IP's address to get a second opinion on its location.
- **What You Do**: Input the IP address and look it up.

![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/0de57446-a694-4b84-864e-91586075cc01)
![image](https://github.com/TheCyberVault/Email-Header-Analysis/assets/141572056/99f89c0e-f755-4f98-bb24-0322537be1a1)


- **What You're Looking For**: Confirming the email's origin. If everything lines up, great. If not, something's fishy.

### Wrapping Up

After playing digital detective, you should have a clearer picture. If too many things don't add up, it's probably best to steer clear of the email

Remember, when in doubt, don't click any links or download attachments. Better safe than sorry in the digital world!
