# Heartbeat
## The day our production SQL database ran out of space

### A Ticket is Submitted

A ticket is submitted into the IT helpdesk stating something ambiguous about a possible outage in the receiving department, this being a warehouse and an essential part of operations being receiving assets and materials, investigation begins.

Checks:
- DNS Does it resolve? Yes
- Website is it up? Yes.
- Database is it up? Yes.
- WTF?

### A Second Ticket is Submitted

The fulfillment department is reporting an outage of multiple functions... interesting probably related. Problem is escalated to executives, calls ensue, investigation interrupted still no answers.

### Root Cause
Connect to production database, immediately see error on system. 
`OUT OF SPACE.`

### Remediation
> This is a virtual machine, I can expand the drive as needed.
- Access Cloud Portal
- Forget vApps aren't managed there and access your vCloud
- Expand drive
- Power up machine, adjust drive partition
- ???
- Profit


