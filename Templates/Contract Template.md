# Contract: GBC-<% tp.date.now("YYYY") %>-<% await tp.system.prompt("Client Name/ID") %>

**Contract ID:** GBC-<% tp.date.now("YYYY") %>-{{CONTRACT_NUMBER}}

---

## Client

- **Name / Colony:** <% await tp.system.prompt("Client Name and Colony") %> 
- **Customer Level (0–4):** <% await tp.system.prompt("Customer Level") %>

---

## Type of Service
<% await tp.system.prompt("Type of Service") %>  
*(e.g. Construction, Escort, Delivery, etc.)*

---

## Objective
<% await tp.system.prompt("Objective") %>
*(Describe clearly what the client wants done.)*

---

## Conditions / Special Requirements
<% await tp.system.prompt("Conditions and Special Requirements") %> 
*(Special instructions, time limits, secrecy clauses, etc.)*

---

## Payment

- **Base Price:** <% await tp.system.prompt("base price") %>  Ʉ 
- **Discount:** <% await tp.system.prompt("Discount") %> Ʉ 
- **Total Agreed:** <% await tp.system.prompt("Total Agreed") %> Ʉ

---

## Payment Method

<% await tp.system.prompt("Payment method (if items Please list)") %> 

---

## Company Resources Assigned
<% await tp.system.prompt("Assigned Company Resources") %> 

---

## Deadlines

- **Start Date:** <% tp.date.now("YYYY-MM-DD") %>  
- **Estimated Completion:** <% await tp.system.prompt("Estimated Completion") %> 

---

## Signatures


- **Client Signature:** {{CLIENT_SIGNATURE}}  


---

- **Grey Banner Signature:** 
```
╔══════════════════════════════════╗
║ ██████╗ ██████╗  ██████╗         ║
║██╔════╝ ██╔══██╗██╔════╝         ║
║██║  ███╗██████╔╝██║              ║
║██║   ██║██╔══██╗██║              ║
║╚██████╔╝██████╔╝╚██████╗         ║
║ ╚═════╝ ╚═════╝  ╚═════╝         ║
║                                  ║
║  GREY BANNER COMPANY             ║
║  Strength • Honor • Discretion   ║
╚══════════════════════════════════╝
