# Detection and pose estimation of auto-rickshaws from images
Auto-rickshaws constitute the most common and cheap form of public transport vehicle in the south Asian countries and especially in India. Auto-rickshaws are largely  supported by the governing bodies in Indian cities as a public transportation module  due to its high fuel efficiently and very low carbon emission. Moreover governments are providing huge subsidies to bring out electric versions of auto-rickshaws on the avenues and even online taxi booking platform OLA introduced auto-rickshaws in cities of UK. However, when it comes to road scene understanding algorithms and intelligent transportation, most of the publicly available datasets are based on the vehicle types of Europe and north American countries, and hence it find less adaptable to scenarios of Indian roads. In the light of these facts, developing intelligent transportation systems based on road scene understanding for Indian subcontinent remains incomplete without detection and identification of vehicle class: auto-rickshaws. This repo contains the dataset and trained detector models used to implement detection and pose estimation of this specific vehicle type.

# Dataset
1. [Images](https://1drv.ms/u/s!AkQHlKGkKEJshkou9FIMNFA3JAkf?e=fEYmUk)
2. [Annotations](https://1drv.ms/u/s!AkQHlKGkKEJshklbt1OUsLJbmaw6?e=40Ij02)

# Detetctors
We trained following detectors and their revised versions to detect auto-rickshaws:
- [ACF](https://vision.cornell.edu/se3/wp-content/uploads/2014/09/DollarPAMI14pyramids_0.pdf)
- [LDCF](https://arxiv.org/pdf/1406.1134)
- [Faster R-CNN](https://arxiv.org/abs/1506.01497)
- [Feature Pyramid Network](https://arxiv.org/abs/1612.03144)
- [RetinaNet](https://arxiv.org/abs/1708.02002)
