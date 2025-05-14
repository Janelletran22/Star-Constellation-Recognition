This is a working repo with development in an optimized lightweight constellation recognition system through systematic experimentation with data preprocessing, optimizer selection, and YOLO architecture variants. Our methodology encompasses rigorous evaluation of data modification techniques, comparison of different optimizers (Adam, AdamW, SGD), and assessment of YOLO architectures (YOLOv8n, YOLOv11n, YOLOv8s, YOLOv11s) to achieve optimal performance while maintaining computational efficiency.

Through systematic data preprocessing modifications, we achieved substantial performance gains with 4.56% improvement in mAP50 (from 0.929 to 0.9746), 2.70% increase in precision, and recovery of recall from 0.904 to 0.9. Our optimizer comparison reveals AdamW as the superior choice, delivering mAP50 of 0.975. Architectural evaluation demonstrates YOLOv11s as the optimal variant, achieving mAP50 of 0.93 with 0.977 recall. The combination of optimized data preprocessing, AdamW optimizer, and YOLOv11s architecture produces our best-performing model with dramatic improvements: 11.90% increase in precision (0.977), 8.00% increase in recall (0.976), and 7.20% enhancement in F1 score (0.952).

These results enable practical deployment of constellation recognition on resource-constrained devices, making astronomical tools more accessible for educational outreach, citizen science projects, and field astronomy. The lightweight nature of our optimized model opens new possibilities for real-time sky mapping applications, automated telescope guidance systems, and interactive astronomy learning platforms on mobile devices.


In this repo includes folders with the output results of each type of architecture and optimizer tested. The repo also has every individual code to run each instance inside the star_constellation_alg.ipynb

The datasets used in this repo can majorily be found in the website: https://universe.roboflow.com/my-workspace-1ekf0/constellation-finder
