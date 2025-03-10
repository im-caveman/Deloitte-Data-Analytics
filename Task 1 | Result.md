# Task One Result
I completed the task in these steps:
* Uploaded the `Telemetry Data` as `json` file.
* Created a Calculated Field called `unhealthy` using formula
    `IF[Status]="unhealthy" THEN 10 ELSE 0 END`
* Since messages are sent every 10 minutes, we set this measure to 10 for every unhealthy status received.

---
## CREATE A CHART "Downtime Per Factory"
* We will use a classic bar-chart for that.
* `Factory` field to the `Columns Field`.
* `Unhealthy` field to the `Rows Field`.
  
![Downtime per Factory](https://github.com/user-attachments/assets/30805e61-ce6c-47cd-b6cd-8d34b6eecdb9)

---
## CREATE A CHART "Downtime per Device Type"
* Create a new sheet.
* We will again use a classic bar-chart for that.
* `Device Type` field in the `Column` field
* `Unhealthy` field in the `Rows` field.

![downtime per device type](https://github.com/user-attachments/assets/9cc13a86-9bae-4691-a06b-45acb5acc53b)


---
## CREATED A DASHBOARD
* Dragged Sheet-1 on top and Sheet-2 on bottom of the dashboard's canvas

![dashboard](https://github.com/user-attachments/assets/a12dc0d2-5de9-4fb5-b427-c3631af31d90)

---
## FINALLY
* Synced the 2 Charts and whenever we select a factory in the first(top) chart - the bottom chart shows only the downtime of all machines there.
* Then selected the factory with most downtime

![task 1 (Deloitte)](https://github.com/user-attachments/assets/db88bf5d-be1c-4239-aff3-494173583b63)


