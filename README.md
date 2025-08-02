# Stellar Incident Reporting Contract

This repository contains a Soroban smart contract deployed on the Stellar testnet for reporting and retrieving incidents.

## Contract Address

```
CA5KTWZW6EK5HL4MAB7DXBYBIQZ7JQ3MAKH6UQXQL256P2I44PFR6MLS
```

## Available Methods

### 1. `report_incident(report: string) -> Incident`

Report a new incident with a text message.
**Arguments:**

* `report`: Description of the incident

### 2. `get_incident(incident_id: u32) -> Incident`

Retrieve an incident by its ID.

### 3. `get_total_incidents() -> u32`

Returns the total number of incidents reported.

## Demo

View the usage demo here:
[https://drive.google.com/drive/folders/1DAzuxIHUYtEzvkzHNYDM2gAVSNvAg50b](https://drive.google.com/drive/folders/1DAzuxIHUYtEzvkzHNYDM2gAVSNvAg50b)

---

## Setup Instructions

```bash
# Clone the repository
git clone https://github.com/virtualvasu/stellar_contracts_incident.git

# Navigate into the directory
cd stellar_contracts_incident
```

---

## License

MIT
