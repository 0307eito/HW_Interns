# 360° photo

<iframe src="psv_viewer.html" style="width: 100%; height: 600px;" frameborder="0"></iframe>

<div id="viewer" style="width: 100vw; height: 100vh;"></div>

<script type="importmap">
{
    "imports": {
        "three": "./node_modules/three/build/three.module.js",
        "@photo-sphere-viewer/core": "./node_modules/@photo-sphere-viewer/core/index.module.js"
    }
}
</script>

<script type="module">
    import { Viewer } from '@photo-sphere-viewer/core';

    const viewer = new Viewer({
        container: document.querySelector('#viewer'),
        panorama: '_images/photo2.png' // 替换为你360度全景照片的路径






    });
</script>




![Description of the image](photo2.png)
