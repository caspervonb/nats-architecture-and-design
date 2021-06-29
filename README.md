![NATS](large-logo.png)

# NATS Architecture And Design

This repo is used to capture architectural and design decisions as a reference of the server implementation and expected client behavior.

For now this will consist of Architecture Decision Records (ADRs), but main include proposals. Issues will be used to track work needed for ADRs to be completed or for design discussions.

# Architecture Decision Records

The [server](server) directory holds ADRs that document major decisions made in the design of the NATS Server. These decisions are used to design server operation and client behavior.

The [client](client) directory holds ADRS that document suggested client API and behavior. Not all API and behavior is appropriate or implementable for all programming languages or paradigms, 
but it is a best effort to define behavior in order to provide consistency between clients.

## When to write an ADR

Not every little decision needs an ADR, and we are not overly prescriptive about the format.
The kind of change that should have an ADR are ones likely to impact many client libraries, server configuration, security, deployment
and those where we specifically wish to solicit wider community input.

## Template

Please see the [template](adr-template.md). The template is a guideline, a suggestion. Feel free to add sections as you feel appropriate. Look at the other ADRs for examples.

## Repositories

Server [nats-server](https://github.com/nats-io/nats-server)

Reference implementation [nats.go](https://github.com/nats-io/nats.go)

Java Client [nats.java](https://github.com/nats-io/nats..java)

.NET / C# client [nats.net](https://github.com/nats-io/nats.net)

Java Script [nats.ws](https://github.com/nats-io/nats.ws) [nats.deno](https://github.com/nats-io/nats.deno) 

C Client [nats.c](https://github.com/nats-io/nats.c)

Python3 Client for Asyncio [nats.py](https://github.com/nats-io/nats.py)

### Client Tracking

There is a [Client Feature Parity](https://docs.google.com/spreadsheets/d/1VcYcKqwOp8h8zZwNSRXMS5wrdA1jZz6AumMTHZbXrmY/edit#gid=1032495336) spreadsheet that tracks the clients somewhat, but it is not guaranteed to be complete or up to date. 
