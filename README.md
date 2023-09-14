# DQNdot: A Deep Learning Framework for Multi-Object Tracking in UAV-Enabled Aerial Surveillance

Welcome to the official repository of DQNdot, a deep learning framework for multi-object tracking in UAV-enabled aerial surveillance. This framework combines state-of-the-art components, including YOLOv8, UAVMOT, Kalman filter, and Hungarian Matching Algorithm, to provide robust and efficient object tracking capabilities for aerial surveillance applications.

## Getting Started
To get started with DQNdot and access the full code and datasets, navigate to my 
 ## [Code Space - Redesigned Guide](https://redesigned-guide-qwv9gg66r97c95q5.github.dev).
Here, you will find comprehensive instructions on setting up the framework and running multi-object tracking experiments.

## Overview

DQNdot leverages the power of deep reinforcement learning and computer vision to address the challenges of tracking multiple objects in UAV (Unmanned Aerial Vehicle) imagery. It offers the following key features:

- **YOLOv8 Integration**: DQNdot incorporates YOLOv8, a cutting-edge object detection model, as its backbone for accurate object detection in aerial imagery.

- **UAVMOT**: UAVMOT (UAV Multi-Object Tracking) is a specialized tracking module designed to track multiple objects efficiently in UAV imagery.

- **Kalman Filter**: The Kalman filter is used for state estimation, providing smoother and more reliable object trajectories.

- **Hungarian Matching Algorithm**: DQNdot utilizes the Hungarian Matching Algorithm to associate object detections across frames, ensuring accurate tracking.

## Workflow

[Workflow](./mfig1.png)

The workflow of DQNdot involves object detection, state estimation, and object association to achieve multi-object tracking in UAV imagery. For a detailed explanation of the workflow, please refer to the [Workflow Documentation](#workflow-documentation).

## Performance Comparison

[Performance Comparison](./mfig2.png)

DQNdot's performance is compared with LDVRL and DQN+Deep Sort in aerial surveillance scenarios. The results demonstrate the effectiveness of DQNdot in tracking multiple objects simultaneously.

## Performance in Datasets

[Performance in VISDRONE and UAVDT](./mfig3.png)

DQNdot's performance in the VISDRONE and UAVDT benchmark datasets showcases its ability to handle real-world UAV-enabled aerial surveillance scenarios. For detailed performance metrics, please refer to the [Performance Metrics](#performance-metrics) section.



## Documentation

For detailed documentation, installation instructions, and usage examples, please refer to the [DQNdot Documentation](https://github.com/smartinprabhu/DQNdot/docs).

## Contributing

We welcome contributions from the community! If you'd like to contribute to DQNdot's development or report issues, please visit the [Contributing Guidelines](https://github.com/smartinprabhu/DQNdot/CONTRIBUTING.md).

## License

DQNdot is available under the [AGPL-3.0 License](https://github.com/smartinprabhu/DQNdot/LICENSE). For commercial use and enterprise licensing, please contact us.

## Contact

For any questions, bug reports, or collaboration inquiries, please join our [Discord community](https://discord.gg/2wNGbc6g9X).

---

**Note**: This README provides an overview of DQNdot. For the full documentation and code, please visit the [DQNdot GitHub Repository](https://github.com/smartinprabhu/DQNdot).
