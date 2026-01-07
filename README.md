🔍 YOLO-Assisted PCB Missing Component Detection System
📌 Overview

This project implements an automated PCB inspection system to detect missing electronic components on a printed circuit board (PCB).
It combines YOLO-based component detection 🤖 with golden-image-based image differencing 🖼️ to identify both where a component is missing and what type of component it is.

The system is reference-based and does not require retraining the detection model for missing components.

💡 Key Idea

🟢 Golden PCB Image: Fully assembled, correct board (reference)

🔵 Test PCB Image: Board under inspection

📦 YOLO detects all components on the golden PCB

🔍 Image differencing is applied inside component regions

❌ Significant difference → component marked as missing

🏷️ Component identity is inherited from the golden image

✨ Features

🔎 Detects missing PCB components

🧠 Identifies which component is missing (resistor, capacitor, IC, etc.)

🤖 Uses YOLO object detection

🚫 No retraining required for missing components

🌤️ Tolerant to minor lighting variations
