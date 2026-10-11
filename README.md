
## Overview:

This is a person detection project that streams from 32-cam and process live feed data with the power of friendship(TensorFlow Lite) into motor driver. Use esp32-cam ov3660 since its better for AI stuffs.

## File Tree Structure:

esp32_person_project/
├── person_detector_64x64.ino
├── model_data.h)
├── TensorFlowLite_ESP32.h
├── utility.h
└── tensorflow/
    └── lite/
        ├── micro/
        │   ├── all_ops_resolver.h
        │   └── micro_interpreter.h
        ├── schema/
        │   └── schema_generated.h
        └── version.h
        
## Dataset Resources:

- https://www.csc.kth.se/cvap/actions/
- https://drive.google.com/file/d/1I7OjhaomWqd8Quf7o5suwLloRlY0THbp/view
- https://data.caltech.edu/records/f6rph-90m20
- https://www.cis.upenn.edu/~jshi/ped_html/
- https://platform.ultralytics.com/ultralytics/yolo26/yolo26x

## TensorFlow by:

- https://github.com/tensorflow/tflite-micro-arduino-examples#how-to-install
- https://github.com/tanakamasayuki/Arduino_TensorFlowLite_ESP32
