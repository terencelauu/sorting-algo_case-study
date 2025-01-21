# Sorting Algorithm 

### Problem 1

Allocating medical staff, equipment, and facilities optimally to provide quality healthcare services while balancing patient demand and operational efficiency is a critical resource allocation problem in healthcare management.

Propose two algorithms for scheduling healthcare professionals' shifts and assigning operating rooms based on a hospital's needs and constraints.
Given below are the list of the professional healthcare (Table 1) and operating rooms (Table 2) available for attending patients. Table 3 is a sample of patients requiring treatment. Use these datases to demonstrate your solutions. Assume any week of the year 2023/2024 for the scheduling.

Table 1: List of Healthcare Professionals and their availability
| Staff ID | Name          | Specialty        | Shift Availability        |
| -------- | ------------- | ---------------- | ------------------------- |
| 1        | Dr. Smith     | Cardiologist     | Monday, Wednesday, Friday |
| 2        | Dr. Johnson   | Surgeon          | Tuesday, Thursday         |
| 3        | Nurse Brown   | Anesthetist      | Monday to Friday          |
| 4        | Nurse Miller  | Pedriatric Nurse | Monday, Wednesday, Friday |

Table 2: List of operating rooms and their availability
| Room ID | Room Type      | Availability                     |
|---------|----------------|-----------------------------------|
| 101     | Surgical Room  | Monday to Friday, Morning Shift   |
| 102     | ICU            | Tuesday, Thursday, Night Shift    |
| 103     | Pediatrics     | Monday to Friday, Afternoon Shift |

Table 3: List of patients requiring treatment
| Patient ID | Name          | Specialty Required |
|------------|---------------|--------------------|
| P001       | John Doe      | Surgery            |
| P002       | Helen Jones   | Pediatrics         |
| P003       | Emily Johnson | Cardiology         |
| P004       | Tom Miller    | Surgery            |
| P005       | June Larson   | Surgery            |

<br>

### Problem 2

The packet forwarding problem in network routing refers to the challenge of determining the best path or route for data packets to travel from a source to their intended destination within a network. It involves making decisions at each network node (routers or switches) regarding how to efficiently forward incoming packets toward their target destination.

Propose two algorithms for packet forwarding. Table 4 shows an example of connected network nodes for demonstration. You can assume the packet can travel anywhere within the network and factors such as traffic load and link quality can effect routing performance.

Table 4: Network routing
| Node ID | Node Name | Connected Nodes   | Traffic Load | Link Quality |
|---------|-----------|-------------------|--------------|--------------|
| 001     | Router-A  | 002, 003, 004     | High         | Good         |
| 002     | Router-B  | 001, 003          | Medium       | Fair         |
| 003     | Router-C  | 001, 002, 004     | High         | Excellent    |
| 004     | Router-D  | 001, 003          | Low          | Poor         |

• Node ID: Unique identifier for each network node (router).

• Node Name: Name or label for the network node.

• Connected Nodes: IDs of nodes directly connected to the current node.

• Traffic Load: Current traffic load on the node (e.g., high, medium, low).

• Link Quality: Quality of the connections between nodes (e.g., excellent, good, fair, poor).
