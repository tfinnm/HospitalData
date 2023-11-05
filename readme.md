# EmergencyRoom.Compare Data Set
---

## Structure:
```
 {[
    {
      "name": string,
      "token": string,
            "address": string,
            "coords": {
                "x": float,
                "y": float
            },
            "traumalvl": int,
            "peds": boolean,
            "stroke": "none" | "primary" | "comprehensive",
            "perinatal": boolean,
            "PCI": boolean,
            "burn": boolean
    }
 ]}
```

## Usage:
Make a HTTP/REST request (GET) to `https://raw.githubusercontent.com/tfinnm/HospitalData/main/facilitydata.json` 
