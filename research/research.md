## 3D Reconstruction Research

I studied 3D reconstruction methods this week for PreserveMy.World.

### COLMAP
- **Input:** Multiple photos of the same place from different angles
- **Output:** A 3D point cloud
- I learned it finds matching points across photos and builds a 3D structure from them
- For PMW this could work to reconstruct heritage sites from photos

### NeRF (Neural Radiance Fields)
- **Input:** Multiple images
- **Output:** A neural network that can show the scene from any angle
- I learned it trains a small neural network on the images to predict what the scene looks like from any new viewpoint
- For PMW this gives very detailed results but needs a GPU

### Gaussian Splatting
- **Input:** Images with camera positions
- **Output:** A 3D scene that renders in real time
- I learned it places 3D blobs in space and optimizes them to match the photos, much faster than NeRF
- For PMW this seems the best for real time viewing of preserved locations