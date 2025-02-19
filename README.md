# Delhivery-Case-Study

## About Delhivery

Delhivery is India's largest and fastest-growing fully integrated logistics provider by revenue (Fiscal 2021). Their goal is to build an **operating system for commerce**, leveraging:
- **World-class infrastructure**
- **High-quality logistics operations**
- **Cutting-edge engineering and technology**

The **Data Team** plays a crucial role by **extracting intelligence from data**, helping Delhivery **optimize quality, efficiency, and profitability** compared to competitors.

---

📂 **Dataset Link:** [Download Here]([https://drive.google.com/your-file-link](https://drive.google.com/file/d/1hUfAxSwauSFsF4NtUOMEBArxcyQ7eW2-/view?usp=drive_link))


## Column Profiling

| **Column**                     | **Description**  |
|--------------------------------|----------------|
| `data`                         | Identifies whether the data is training or testing. |
| `trip_creation_time`           | Timestamp of trip creation. |
| `route_schedule_uuid`          | Unique ID for a specific route schedule. |
| `route_type`                   | Transportation type (e.g., FTL, Carting). |
| `trip_uuid`                    | Unique trip ID (a trip may include different source and destination centers). |
| `source_center`                | Source ID of the trip's origin. |
| `source_name`                  | Source name of the trip's origin. |
| `destination_center`           | Destination ID. |
| `destination_name`             | Destination name. |
| `od_start_time`                | Trip start time. |
| `od_end_time`                  | Trip end time. |
| `start_scan_to_end_scan`       | Time taken to deliver from source to destination. |
| `actual_distance_to_destination` | Distance (in km) between source and destination warehouses. |
| `actual_time`                  | Actual time taken to complete delivery (cumulative). |
| `osrm_time`                    | OSRM-predicted time for the shortest route (cumulative). |
| `osrm_distance`                | OSRM-predicted distance for the shortest route (cumulative). |
| `segment_actual_time`          | Time taken for a segment of package delivery. |
| `segment_osrm_time`            | OSRM-predicted time for a segment. |
| `segment_osrm_distance`        | OSRM-predicted distance for a segment. |

🔹 **Unknown Fields:** `is_cutoff`, `cutoff_factor`, `cutoff_timestamp`, `factor`, `segment_factor` (further analysis required).  

---

## Concepts Used

📌 **Feature Engineering**: Creating new features for better analysis.  
📌 **Feature Relationships**: Understanding dependencies between columns.  
📌 **Normalization & Standardization**: Scaling numerical features for consistency.  
📌 **Handling Categorical Values**: Encoding categorical features.  
📌 **Missing Value & Outlier Treatment**: Identifying and handling missing or extreme values.  
