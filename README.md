# test_tasks

Repository for networking lab tasks and diagnostics.
Includes log analysis, network packet (pcap) analysis with Wireshark/TShark, and Docker containers check.

---

## 📝 Tasks

1. **Log Analysis**  
   Analyze system logs from 3 servers (`server-1.txt`, `server-2.txt`, `server-3.txt`) and prepare diagnostic reports.  
   → Results stored in `logs_report/`.

2. **Network Analysis with MTR**  
   Run MTR to check network routes and packet loss.  
   → Results in `mtr_results/`.

3. **Alternative Diagnostics**  
   Perform analysis using `ping` and `traceroute`.  
   → Results in `ping_traceroute_results/`.

4. **PCAP Analysis (Wireshark/TShark)**  
   File `test.pcap` is analyzed for:
   - Protocol hierarchy  
   - DHCP Release sources  
   - STP root bridge priority  
   - DNS errors ("Server failure")  

5. **Docker Containers Check**  
   Task to verify running state of Docker containers with commands like:
   ```bash
   docker ps -a
   docker stats
   docker logs <container_id>

