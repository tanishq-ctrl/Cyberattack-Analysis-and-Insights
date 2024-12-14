# Cybersecurity Analysis and Insights

## Introduction
This repository contains an in-depth analysis of a cybersecurity dataset. The primary goal is to identify patterns, vulnerabilities, and trends in cyberattacks by leveraging various visualizations and statistical insights. The project provides actionable insights for enhancing cybersecurity measures.

## Dataset Description
The dataset includes records of network activity and potential cyberattacks. It contains the following key features:

- **Timestamp**: Date and time of the event.
- **Source IP Address**: The IP address initiating the communication.
- **Destination IP Address**: The target IP address.
- **Source Port**: The port used by the source IP.
- **Destination Port**: The port targeted by the communication.
- **Protocol**: The network protocol used (e.g., TCP, UDP, ICMP).
- **Packet Length**: Size of the network packet.
- **Packet Type**: Indicates the type of packet (Data or Control).
- **Traffic Type**: Categorizes traffic (e.g., HTTP, DNS).
- **Payload Data**: Captures payload content in text format.
- **Anomaly Scores**: Assigned score indicating anomaly level.
- **Severity Level**: Categorizes the severity of the event.
- **Log Source**: Indicates the source generating the log (e.g., Server, Firewall).
- **Temporal Features**: Derived features like Year, Month, Day, Hour, etc.

### Dataset at a Glance
The dataset contains 33 columns, offering rich contextual information for analysis.

---

## Visualizations and Insights

### 1. Top 10 Source IPs
![Top 10 Source IPs](images/top10_sourceips_involved_in_cyberattacks.png)
**Insight**: A small subset of IPs are responsible for a significant number of attacks, indicating possible repeat offenders. Security teams can prioritize monitoring and blocking these IPs.

### 2. Top 10 Destination Ports
![Top 10 Destination Ports](images/top_10_targeted_destination_ports.png)
**Insight**: Frequently targeted ports suggest potential vulnerabilities or widely used protocols. Ports like 80 (HTTP) and 443 (HTTPS) may be high-value targets.

### 3. Distribution of Packet Lengths
![Distribution of Packet Lengths](images/Distribution_of_packet_lengths.png)
**Insight**: The histogram highlights clustering around specific packet sizes, possibly reflecting standard protocol behavior or attack payloads.

### 4. Attack Type vs Severity Level
![Attack Type vs Severity Level](images/Attack_type_vs_severity_level.png)
**Insight**: Certain attack types (e.g., DDoS) are more associated with high-severity incidents. This highlights the need for robust mitigation strategies.

### 5. Hourly Trends in Cyber Attacks
![5. Hourly Trends in Cyber Attacks](images/Hourly_trends_in_cyber_attacks.png)
**Insight**: Peaks during certain hours suggest attackers' schedules or automated attack scripts. Organizations should heighten monitoring during these periods.

### 6. Anomaly Scores by Severity
![Anomaly Scores by Severity](images/Anomally_scores_dist_by_security_level.png)
**Insight**: Higher severity levels align with higher anomaly scores. This validates the effectiveness of anomaly detection systems.

### 7. Top Network Segments
![Top Network Segments](images/top5_network_segments_Attacked.png)
**Insight**: Specific network segments are disproportionately targeted, likely due to their critical functions or vulnerabilities.

### 8. Month-wise Trends
![Month-wise Trends](images/month_wise_distribution_of_Attacks.png)
**Insight**: Seasonal spikes may correlate with global events or specific attack campaigns. Enhanced monitoring is recommended during peak months.

### 9. Alerts Breakdown
![Alerts Breakdown](images/Breakdown_of_Alerts:Warnings.png)
**Insight**: High-frequency alerts indicate common threats, while rare alerts may signify emerging risks.

### 10. Traffic Types
![Traffic Types](images/Distribution_of_traffic_types_in_attacks.png)
**Insight**: Predominant traffic types like HTTP and DNS are natural targets due to their ubiquity in network communications.

### 11. Distribution of Attack Types by Browser
![Distribution of Attack Types by Browser](images/distribution_of_attack_types_browser.png)
**Insight**: Certain browsers are more frequently targeted, likely reflecting their popularity or security gaps.

### 12. Distribution of Attack Types by Device/OS
![Distribution of Attack Types by Device/OS](images/Distribution_of_attack_types_by_device:os.png)
**Insight**: Vulnerabilities are concentrated in specific device/OS combinations, highlighting areas for improvement.

### 13. Top Actions Taken
![Top Actions Taken](images/Top_action_taken_against_attacks.png)
**Insight**: Blocking and isolating are the most frequent responses. This suggests a need to evaluate their effectiveness.

### 14. Protocol Usage Distribution
![Protocol Usage Distribution](images/Distribution_of_protocols.png)
**Insight**: Common protocols like TCP and UDP dominate, underscoring the importance of securing these foundational elements.

---

## Methodology
### Steps Taken:
1. **Data Cleaning**: Handled missing values and standardized formats.
2. **Feature Engineering**: Derived additional temporal features (e.g., Day of Week, Hour).
3. **Visualization**: Created 16 visualizations using Matplotlib and Seaborn to extract meaningful patterns.
4. **Analysis**: Conducted storytelling for each visualization to provide actionable insights.

---

## Conclusion
This analysis offers a comprehensive view of the cyber threat landscape. Key findings include:
- Identifying high-risk IPs, ports, and network segments.
- Unveiling temporal patterns to optimize monitoring efforts.
- Providing insights into attack types and severity levels for targeted defense.

**Recommendations**:
1. Prioritize monitoring high-risk IPs and ports.
2. Fortify vulnerable network segments and devices.
3. Regularly update protocols and browsers to address known vulnerabilities.
4. Leverage anomaly scores to preemptively mitigate high-severity incidents.

This repository serves as a foundational resource for enhancing cybersecurity strategies and decision-making.

