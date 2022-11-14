# DCPNet for Image Enhancement

DCPNet: Deformable Control Point Network for Image Enhancement

# Abstract

In this paper, we propose a novel image enhancement network via learning deformable control points (DCPs). First, we construct global transformation functions (GTFs) by composing DCPs, forming the overall structure of GTFs, and the curve parameters, representing the local curve between each adjacent DCP pair. Specifically, a downsampled image is used as an input and fed into the DCP network (DCPNet) to obtain the parameters for GTFs: The DCP offsets and the curve parameters. Then, we get DCPs from the DCP offsets and connect each adjacent DCP pair by using the curve parameter to construct a GTF for each color channel. Original input images are then transformed based on the resultant GTFs to obtain globally enhanced images. Finally, we feed this intermediate image into the
local enhancement network, which has a U-Net architecture, to produce the spatially enhanced images. Extensive experimental results demonstrate that the proposed method achieves superior results to the state-of-the-art methods on public image enhancement datasets.

# Framework

# Source Codes

It will be available soon.
