# 3D Dust Density Map of the Solar Neighbourhood

This repository contains the 3D dust density map reconstructed in our paper 

## Data Files

### `cube_rho_dust.npy.gz`

The reconstructed 3D dust density field.

- **Format:** Compressed NumPy binary (`.npy.gz`). Load with `np.load()`.
- **Units:** mag pc⁻¹
- **Dimensions:** `241 × 241 × 123` voxels
- **Voxel size:** `8 × 8 × 8 pc³`
- **Spatial coverage:** `X: -960 to 960 pc`, `Y: -960 to 960 pc`, `Z: -488 to 488 pc`
- **Coordinate system:** Galactocentric Cartesian `(X, Y, Z)`, with the Sun at `(0, 0, 0)`

### `density_isosurface_85percent.html`

Interactive 3D visualization of the Local Bubble inner wall (85% density isosurface). Open in any web browser.

### `local_bubble_with_clouds_voxels.html`

Interactive 3D visualization of the Local Bubble cavity and surrounding molecular clouds. Open in any web browser.

## Contact

[Li Xinxin], [lixinxin_adcu@stu.ynu.edu.cn]
