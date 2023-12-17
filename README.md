# ladybird morphology
Unraveling ladybird mysteries through advanced morphological analysis

In the realm of data science, my PhD research takes a deep dive into the intricate world of ladybirds, 
leveraging advanced analytics to unlock the secrets behind their morphological variation. 

## Materials and Methods: Gathering Data Across Auckland

Data collection spans eight field sites in the greater Auckland region, covering both fresh and museum specimens of ladybirds. 
Leveraging ArcMap GIS software, sampling sites were selected, ensuring a comprehensive representation of habitats. 
The dataset comprises ten ladybird species, five native and five introduced, each contributing unique characteristics to the analysis.

## Data Capture: Pixels and Parameters

Ladybird specimens were meticulously photographed using a Nikon DS-U3-Ri1 camera connected to a Leica M205A stereomicroscope. 
These high-resolution images served as the foundation for both size and color analyses. Utilizing ImageJ software, I quantified 
morphological measurements related to body length and width, laying the groundwork for subsequent data-driven insights.

## Ensuring Data Integrity: Repeatability Measures

Data reliability is paramount in the world of data science. Subset analysis involved photographing and scoring ladybirds 
multiple times to establish repeatability. High intraclass correlation coefficients (ICC) for both size and color measurements 
validated the robustness of the dataset.

## Statistical Algorithms: Unraveling Patterns in Ladybird Morphometrics

With data in hand, I applied statistical algorithms to extract meaningful patterns. Principal Component Analysis (PCA) reduced 
morphometric variables to orthogonal axes, providing a holistic representation of size variation. Analyses showcased intriguing trends, 
especially in the width variations across the elytra of introduced ladybirds.

In a complementary simulation to our ladybird morphological study, we ventured into the realm of color diversity. 
Leveraging the alphashape3d package in R, we simulated RGB values to construct 3D objects, representing the intricate color variations within ladybird populations. 
Our simulation aimed to answer a critical question: Are our sample sizes sufficient to capture the true variation within the ladybird population? 
To assess this, we measured the volume of the 3D objects constructed from RGB values, treating each color dimension as a unique axis. The hypothesis was that 
if our sample sizes were adequate, the volume values would eventually plateau as we increased the sample sizes.

## Decoding Ladybird Flight: Geometric Morphometric Analysis of Hind Wing Shape

Diving deeper into the intricacies of ladybird anatomy, I focused on aspect of wing shape. Employing geometric morphometric analysis on the right hind wings, 
I sought to unravel the nuances that define the flight patterns and aerodynamics of these fascinating insects. 
Utilizing the 'geomorph' package in R, I selected six landmarks on the hind wings using the digitize2d function. 
These landmarks were strategically chosen to capture the key features influencing wing shape. Principal components were then derived from the landmark coordinates, 
creating two components that succinctly described the shape variations of the right hind wing. WPC1 and WPC2, the chosen components, 
collectively explained an impressive 77.47% of the total variance in ladybird wing shape. In essence, our geometric morphometric analysis of hind wing shape 
offers a glimpse into the intricate world of ladybird flight dynamics. From subtle shifts in vein lengths to broader changes in wing breadth, 
each component contributes to our understanding of the nuanced adaptations that enable these insects to navigate.

## Colorful Coding: RGB Scores and Visualizations

The color analysis involved translating ladybird hues into RGB scores, creating a visually stunning representation of color variations. 
Leveraging the power of R, 3D plots highlighted the distinctive color patterns within each species. Notably, introduced ladybirds, 
particularly the blue Halmus chalybeus, exhibited higher levels of color variation compared to their native counterparts.
