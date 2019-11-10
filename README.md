# Point Cloud Renderer

Instructions and scripts for rendering point cloud figures shown in **PointFlow: 3D Point Cloud Generation with Continuous Normalizing Flows**.

[[Paper]](https://arxiv.org/abs/1906.12320) [[Project GitHub]](https://github.com/stevenygd/PointFlow).

The script generates a XML file, which describes a 3D scene in the format used by Mitsuba. You will then be able to render it with Mitsuba.

## Dependencies
* Python 3.6
* [Mitsuba Renderer](http://www.mitsuba-renderer.org/)

## Instructions
```bash
# Generate scene XML file
python3.6 pointflow_fig_colorful.py

# Render using Mitsuba
mitsuba mitsuba_scene.xml
```

## Examples
<p float="left">
    <img src="mitsuba_scene.png" height="256"/>
</p>

## Cite
Please consider citing our work if you find it useful:
```latex
@article{pointflow,
 title={PointFlow: 3D Point Cloud Generation with Continuous Normalizing Flows},
 author={Yang, Guandao and Huang, Xun, and Hao, Zekun and Liu, Ming-Yu and Belongie, Serge and Hariharan, Bharath},
 journal={arXiv},
 year={2019}
}
```
