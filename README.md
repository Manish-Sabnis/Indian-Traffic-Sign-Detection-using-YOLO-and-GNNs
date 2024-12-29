# Indian Traffic Sign Detection using YOLO and GNNs

## **Overview**

This project explores the integration of YOLO (You Only Look Once) and Graph Neural Networks (GNNs) for traffic sign detection and graph-based relationship modeling. While YOLO efficiently detects and classifies traffic signs, the GNN processes these detections as nodes in a graph to study potential spatial and semantic relationships between signs.

### Objectives

- **Traffic Sign Detection:** Use YOLO to detect and classify traffic signs in images with high accuracy.
- **Graph-Based Modeling:** Apply GNNs to experiment with graph-based reasoning over detected traffic signs.
- **Exploratory Analysis:** Investigate the potential of GNNs in enhancing understanding of relationships between detected objects.

### Dataset 
Jackulin Mahariba A, Aryan ., July 8, 2024, "(IRTSD-Datasetv1)-Indian Road Traffic Sign Detection dataset", IEEE Dataport, doi: [https://dx.doi.org/10.21227/ap4b-c439](https://dx.doi.org/10.21227/ap4b-c439).

### **Features**

- End-to-end implementation combining YOLO for object detection and GNNs for graph-based analysis.
- Pretrained YOLO weights for accurate traffic sign detection.
- Custom GNN to model relationships between detected signs (experimental).

### Limitations
- This project does not include datasets with explicit contextual information or tasks requiring reasoning.
- The GNN component is exploratory and does not improve detection accuracy or provide actionable context.

### Future Scope
- Extend the dataset to include traffic contexts, such as road layouts or scenarios.
- Use GNNs to reason about traffic scenarios, predict driver intentions, or identify anomalies.
- Explore other graph-based architectures or hybrid models for improved traffic understanding.

### Results
![68_png rf 68210f795099291cde61d641c169903b](https://github.com/user-attachments/assets/d8c5db78-46c7-4cd6-bff7-3951586d8da3)
![163_jpg rf 26651dc69b5d25ea7d22224fd9676cd7](https://github.com/user-attachments/assets/04cc3fd3-ac9d-4f19-9e4d-07553dce3057)
![170_png rf 19b6ea15c5153ad282a004cc55527400](https://github.com/user-attachments/assets/631ba7a7-13cf-4528-b5b4-833aa405b78f)




