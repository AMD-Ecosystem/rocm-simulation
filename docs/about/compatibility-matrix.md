# ROCm-Simulation compatibility matrix

Use this matrix to view the ROCm-Simulation compatibility and system requirements across releases:

| ROCm-Simulation version | Operating system | ROCm version | Python version | AMD Instinct GPU | Supported components  |
|--------------|------------------|--------------|----------------|----------|----------------|
| 25.11 | <ul><li>Ubuntu 22.04</li><li>Ubuntu 24.04</li></ul> | 7.0.0 | 3.12 | MI300X (GPU target gfx942) | <ul><li>[Taichi v1.8.0b2](https://rocm.docs.amd.com/projects/taichi-internal/en/docs-25.11/install/taichi-install.html)</li><li>[GSplat v1.5.3](https://rocm.docs.amd.com/projects/gsplat-internal/en/docs-25.11/install/gsplat-install.html)</li></ul> |
| 25.10 | <ul><li>Ubuntu 22.04</li><li>Ubuntu 24.04</li></ul> | <ul><li>6.3.2</li><li>6.4.3</li></ul> | <ul><li>3.10</li><li>3.12</li></ul> | <ul><li>MI250X, MI210 (GPU target gfx90a)</li><li>MI300X (GPU target gfx942)</li></ul> | <ul><li>[Taichi v1.8.0b1](https://rocm.docs.amd.com/projects/taichi-internal/en/docs-25.10/install/taichi-install.html)</li><li>[GSplat v1.5.3](https://rocm.docs.amd.com/projects/gsplat-internal/en/docs-25.10/install/gsplat-install.html)</li></ul> |

<table><thead>
  <tr>
    <th>ROCm-Simulation version</th>
    <th>Operating system (Ubuntu)</th>
    <th>ROCm version</th>
    <th>Python version</th>
    <th>AMD Instinct GPU</th>
    <th>Supported components</th>
  </tr></thead>
<tbody>
  <tr>
    <td rowspan="2">25.11</td>
    <td>22.04, 24.04</td>
    <td>6.4.3, 7.0.0</td>
    <td>3.10, 3.12</td>
    <td>MI300X (GPU target: gfx942)</td>
    <td>[Taichi v1.8.0b2](https://rocm.docs.amd.com/projects/taichi-internal/en/docs-25.11/install/taichi-install.html)</td>
  </tr>
  <tr>
    <td>24.04</td>
    <td>7.0.0</td>
    <td>3.12.3</td>
    <td>MI355X, MI325X, MI300X, MI250X, MI210 (GPU targets: gfx950, gfx942, gfx90a)</td>
    <td>[GSplat v1.5.3](https://rocm.docs.amd.com/projects/gsplat-internal/en/docs-25.11/install/gsplat-install.html)</td>
  </tr>
  <tr>
    <td rowspan="2">25.10</td>
    <td>24.04</td>
    <td>6.3.2</td>
    <td>3.10.12</td>
    <td> MI250X, MI210 (GPU target: gfx90a)</td>
    <td>[Taichi v1.8.0b1](https://rocm.docs.amd.com/projects/taichi-internal/en/docs-25.10/install/taichi-install.html)</td>
  </tr>
  <tr>
    <td>24.04</td>
    <td>6.4.3</td>
    <td>3.12</td>
    <td>MI300X (GPU target: gfx942)</td>
    <td>[GSplat v1.5.3](https://rocm.docs.amd.com/projects/gsplat-internal/en/docs-25.10/install/gsplat-install.html)</td>
  </tr>
</tbody>
</table>