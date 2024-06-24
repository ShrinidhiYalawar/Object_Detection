# Object_Detection
In this article, we present the object detection application of YOLOv5, including the detection of people, vehicles, and animals in various environments. Test the performance of the method on the COCO dataset and make it clearer and faster compared to YOLO's previous model. 
Our outcome shows that YOLOv5 achieves good modern performance for a variety of sensing applications, including surveillance, robotics, and autonomous driving. Additionally, we provide a comprehensive review of the algorithm's strengths and weaknesses and discuss future directions for improving its performance. Overall, this article demonstrates the potential of YOLOv5 to be a powerful tool for object detection in real-world applications.
Object recognition and detection has been an important problem for a long time for many different industries, including the medical field, the security industry, and the transportation sector. This issue, however, takes on a greater level of significance for people who are blind or have some other form of visual impairment.
According to estimates by the World Health Organization (WHO), at least 2.2 billion people globally suffer from some form of near or distance vision impairment, with associated annual productivity losses of around $411 billion. 
People who are visually impaired face a wide variety of difficulties on a daily basis. These challenges can range from difficulties with mobility and orientation to difficulties accessing information and services. 
One of the most significant issues that individuals with visual impairment face on a daily basis is related to the use of public transportation, with the difficulty of getting to their destination, followed by the inconvenience and then safety concerns.   
In the context of public bus transportation, people with visual impairment require information about their surroundings and any visible details at bus stops and terminals, such as schedules and routes, in order to use the system independently and safely.
We proposed a lightweight and high-accuracy bus detection model based on an improved YOLOv5 model; 
We integrated the GhostConv and C3Ghost Modules into the YOLOv5 network to reduce the number of parameters and floating-point operations per second (FLOPs), ensuring the detection accuracy while reducing the model parameters;
We added the SimSPPF module to replace the SPPF in the YOLOv5 backbone for increased computational efficiency and accurate object detection capabilities; 
We developed a Slim scale detection model by modifying the original YOLOv5 structure to make the model more efficient and faster, which is critical for real-time object detection applications;
The experimental results showed that the Improved-YOLOv5 outperformed the original YOLOv5 in terms of the precision, recall, and mAP@0.5;
Further analysis of the model complexity revealed that the Improved-YOLOv5 was more efficient due to fewer FLOPS, fewer parameters, less memory usage, and faster inference time capabilities; 
The proposed model is smaller and more feasible to implement in resource-constrained mobile devices and a promising option for bus detection systems.
