# 🪨 Mineral Mass Detection

*NOTE: During my experience in the mining sector, I participated in the development of a visual inspection system using machine vision to detect the presence of mineral material. Out of respect for confidentiality, no images or technical details of the actual system are included. The documentation presented here is a representative simulation developed by me for demonstration purposes.*

This project implements a simple yet effective computer vision algorithm designed to **detect the presence of mineral material** on a conveyor belt using visual data from a camera. The goal is to provide a lightweight, non-invasive system to monitor belt occupancy and assist in process automation and decision-making.

---

## 🎯 Objective

The main goal of this algorithm is to **automatically identify whether there is material present** on a moving conveyor belt in real time. This information can be used to:

- Detect gaps or empty sections in the material flow
- Trigger alarms or events in case of blockages or feeding issues
- Optimize production by monitoring mineral throughput visually

---

## 🧠 How It Works

1. A video or live camera feed captures frames of the conveyor belt.
2. Each frame is processed using simple image analysis techniques.
3. The algorithm detects whether the belt section is occupied or empty.
4. Detection results can be visualized or used to trigger actions in external systems.

      > Simulated images.

<div align="center">

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/2fe0c630-44ab-4368-8056-035800cf4b89" width="380"/></td>
    <td><img src="https://github.com/user-attachments/assets/86f755e9-f459-46b3-bd7b-f278f312aa42" width="300"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Detection</strong></td>
    <td align="center"><strong>Non Detection Filter</strong></td>
  </tr>
</table>

</div>


> The system is designed to work with basic industrial cameras under standard lighting conditions and can be adapted to different environments with minimal calibration.

---

## 🛠️ Technologies Used

- Python 3.x  
- OpenCV for image processing  
- NumPy for matrix and array operations  
- Pandas

---

## 📊 Impact

The implementation of this algorithm brings several benefits to industrial operations:

- 🔍 **Real-time Monitoring**  
  Enables continuous supervision of conveyor belt activity without manual inspection.

- ⚠️ **Early Detection of Flow Issues**  
  Quickly identifies when there’s no material on the belt, helping detect blockages, feeding problems, or interruptions in the process.

- 💡 **Supports Automation**  
  Can be integrated into a larger system to automatically trigger alerts, control feeders, or adjust downstream processes.

- 💰 **Low-Cost and Scalable**  
  Requires only a basic camera and a lightweight algorithm, making it ideal for plants looking to modernize without large infrastructure investments.

> In summary, this project offers a practical and scalable way to improve production visibility and reduce operational risks in mineral handling systems.
