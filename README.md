# DevOps Task 7 – Monitor System Resources using Netdata

## 📌 Task Objective
The goal of this task was to install and run **Netdata** to monitor system performance metrics such as CPU usage, memory usage, disk activity, and network statistics, and then capture screenshots of the dashboard.

---

## 🛠 Steps Performed

1. **Pulled & Ran Netdata using Docker**
   ```bash
   docker run -d --name netdata -p 19999:19999 netdata/netdata


## Accessed the Dashboard

Opened browser and visited:
http://localhost:19999

Clicked Skip and use the dashboard anonymously to bypass login.


## Explored Metrics

Checked overall metrics: CPU usage, RAM usage, system load, network I/O, disk I/O.
Navigated into CPU section for detailed performance graphs.

## Captured Screenshots

dashboard-overview.png → main metrics page.
cpu-details.png → detailed CPU performance chart.

## 📷 Screenshots

Screenshots are stored in the screenshots folder:

dashboard-overview.png
cpu-details.png

## 📚 Learnings

Netdata provides real-time, per-second system monitoring.
It can run easily in Docker and be accessed through a browser.
Useful for quick diagnostics and continuous performance monitoring.

## 🔗 Access

Local dashboard URL: http://localhost:19999

