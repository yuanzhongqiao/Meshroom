<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><a target="_blank" rel="noopener noreferrer" href="/alicevision/Meshroom/blob/develop/docs/logo/banner-meshroom.png"><img src="/alicevision/Meshroom/raw/develop/docs/logo/banner-meshroom.png" alt="Meshroom - 3D 重建软件" style="max-width: 100%;"></a></h1><a id="" class="anchor" aria-label="永久链接：" href="#"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://bestpractices.coreinfrastructure.org/projects/2997" rel="nofollow"><img src="https://camo.githubusercontent.com/7ad4e8dc0f1be8505802a0f1026e2f7923faf77a2649dcd022ac4966486fc4b1/68747470733a2f2f626573747072616374696365732e636f7265696e6672617374727563747572652e6f72672f70726f6a656374732f323939372f6261646765" alt="CII 最佳实践" data-canonical-src="https://bestpractices.coreinfrastructure.org/projects/2997/badge" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/alicevision/AliceVision"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Meshroom 是一款基于AliceVision</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">摄影测量计算机视觉框架</font><font style="vertical-align: inherit;">的免费开源 3D 重建软件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="http://alicevision.github.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在AliceVision 网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上了解有关管道的更多详细信息</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 sketchfab 上查看</font></font><a href="http://sketchfab.com/AliceVision" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管道的结果</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持续集成：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视窗：</font></font><a href="https://ci.appveyor.com/project/AliceVision/meshroom/branch/develop" rel="nofollow"><img src="https://camo.githubusercontent.com/db20417d7d5e05861fe0165a1fdcb61dac8c81c32019f6f1124532b4c769d7f1/68747470733a2f2f63692e6170707665796f722e636f6d2f6170692f70726f6a656374732f7374617475732f32357364376c6672337630726e766e692f6272616e63682f646576656c6f703f7376673d74727565" alt="构建状态" data-canonical-src="https://ci.appveyor.com/api/projects/status/25sd7lfr3v0rnvni/branch/develop?svg=true" style="max-width: 100%;"></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux：</font></font><a href="https://travis-ci.org/alicevision/meshroom" rel="nofollow"><img src="https://camo.githubusercontent.com/980a88078d81083bd11b7c3ad40d11d918ced69a48dec480346fa9ddb8f66465/68747470733a2f2f7472617669732d63692e6f72672f616c696365766973696f6e2f6d657368726f6f6d2e7376673f6272616e63683d646576656c6f70" alt="构建状态" data-canonical-src="https://travis-ci.org/alicevision/meshroom.svg?branch=develop" style="max-width: 100%;"></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">摄影测量</font></font></h2><a id="user-content-photogrammetry" class="anchor" aria-label="永久链接：摄影测量" href="#photogrammetry"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">摄影测量是根据照片进行测量的科学。它从一组无序的照片或视频中推断出场景的几何形状。摄影是将 3D 场景投影到 2D 平面上，丢失深度信息。摄影测量的目标就是扭转这个过程。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="http://alicevision.github.io/#photogrammetry" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管道步骤的介绍</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动的</font></font></h2><a id="user-content-manual" class="anchor" aria-label="永久链接：手册" href="#manual"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://meshroom-manual.readthedocs.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://meshroom-manual.readthedocs.io</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教程</font></font></h2><a id="user-content-tutorials" class="anchor" aria-label="永久链接：教程" href="#tutorials"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://www.youtube.com/watch?v=v_O6tYKQEBA" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><a href="http://www.mikrosimage.com" rel="nofollow"><font style="vertical-align: inherit;">Meshroom： Mikros Image</font></a><font style="vertical-align: inherit;">的</font><a href="https://www.youtube.com/watch?v=v_O6tYKQEBA" rel="nofollow"><font style="vertical-align: inherit;">开源 3D 重建软件</font></a></font><a href="http://www.mikrosimage.com" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Meshroom 软件的整体介绍。</font></font></p>
<ul dir="auto">
<li><a href="https://sketchfab.com/blogs/community/tutorial-meshroom-for-beginners" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><a href="http://www.mikrosimage.com" rel="nofollow"><font style="vertical-align: inherit;">Mikros Image</font></a><font style="vertical-align: inherit;">的</font><a href="https://sketchfab.com/blogs/community/tutorial-meshroom-for-beginners" rel="nofollow"><font style="vertical-align: inherit;">Sketchfab 上的 Meshroom 教程</font></a></font><a href="http://www.mikrosimage.com" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">详细教程，重点介绍 2019.1 版本的功能。</font></font></p>
<ul dir="auto">
<li><a href="https://www.youtube.com/watch?v=1D0EhSi-vvc" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">摄影测量 2 – 只需使用手机/相机即可进行 3D 扫描，比以往更简单、更好！</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由</font></font><a href="https://blog.prusaprinters.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Prusa 3D 打印机提供</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Meshroom 摄影测量实践的总体介绍。</font></font></p>
<ul dir="auto">
<li><a href="https://www.youtube.com/watch?v=k4NTf0hMjtY" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何轻松免费地进行 3D 照片扫描！作者</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://www.youtube.com/channel/UCG8AxMVa6eutIGxrdnDxWpQ" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CG 极客</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总体介绍了 Meshroom 的原型测量实践，并详细介绍了如何在 Blender 中进行重构。</font></font></p>
<ul dir="auto">
<li><a href="https://www.youtube.com/watch?v=eiEaHLNJJ94" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><a href="https://moviola.com" rel="nofollow"><font style="vertical-align: inherit;">Moviola</font></a><font style="vertical-align: inherit;">的</font><a href="https://www.youtube.com/watch?v=eiEaHLNJJ94" rel="nofollow"><font style="vertical-align: inherit;">网状房间生存指南</font></a></font><a href="https://moviola.com" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍 Meshroom 软件，重点介绍如何使用它进行匹配移动。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定制化</font></font></h2><a id="user-content-customization" class="anchor" aria-label="永久链接：定制" href="#customization"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定制管道</font></font></h3><a id="user-content-custom-pipelines" class="anchor" aria-label="永久链接：自定义管道" href="#custom-pipelines"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在用户界面中创建自定义管道并将其另存为模板：</font></font><code>File &gt; Advanced &gt; Save As Template</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。您可以将</font></font><code>MESHROOM_PIPELINE_TEMPLATES_PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量定义到特定文件夹，以使这些管道在 Meshroom 中可用。在 Meshroom 标准预编译版本中，您还可以直接在</font></font><code>lib/meshroom/pipelines</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义节点</font></font></h3><a id="user-content-custom-nodes" class="anchor" aria-label="永久链接：自定义节点" href="#custom-nodes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在 python 中创建自定义节点，并使用环境变量使其在 Meshroom 中可用</font></font><code>MESHROOM_NODES_PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。
以下是</font><font style="vertical-align: inherit;">从 Meshroom 启动 Blender 渲染的</font></font><a href="/alicevision/Meshroom/blob/develop/meshroom/nodes/blender/ScenePreview.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。在 Meshroom 标准预编译版本中，您还可以直接在</font></font><code>lib/meshroom/nodes</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.为了被 Meshroom 识别，带有节点的自定义文件夹应该是一个 Python 模块（</font></font><code>__init__.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要一个文件）。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目在 MPLv2 下发布，请参阅</font></font><a href="/alicevision/Meshroom/blob/develop/COPYING.md"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">COPYING.md</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h2><a id="user-content-citation" class="anchor" aria-label="永久链接：引文" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您将此项目用于出版物，请引用该</font></font><a href="https://hal.archives-ouvertes.fr/hal-03351139" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@inproceedings{alicevision2021,
  title={{A}liceVision {M}eshroom: An open-source {3D} reconstruction pipeline},
  author={Carsten Griwodz and Simone Gasparini and Lilian Calvet and Pierre Gurdjos and Fabien Castan and Benoit Maujean and Gregoire De Lillo and Yann Lanthony},
  booktitle={Proceedings of the 12th ACM Multimedia Systems Conference - {MMSys '21}},
  doi = {10.1145/3458305.3478443},
  publisher = {ACM Press},
  year = {2021}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@inproceedings{alicevision2021,
  title={{A}liceVision {M}eshroom: An open-source {3D} reconstruction pipeline},
  author={Carsten Griwodz and Simone Gasparini and Lilian Calvet and Pierre Gurdjos and Fabien Castan and Benoit Maujean and Gregoire De Lillo and Yann Lanthony},
  booktitle={Proceedings of the 12th ACM Multimedia Systems Conference - {MMSys '21}},
  doi = {10.1145/3458305.3478443},
  publisher = {ACM Press},
  year = {2021}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取项目</font></font></h2><a id="user-content-get-the-project" class="anchor" aria-label="永久链接：获取项目" href="#get-the-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以</font></font><a href="https://github.com/alicevision/meshroom/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载最新版本的预编译二进制文件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想自己构建它，请参阅</font></font><a href="/alicevision/Meshroom/blob/develop/INSTALL.md"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">INSTALL.md</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来设置项目和先决条件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取源代码并安装运行时要求：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone --recursive git://github.com/alicevision/meshroom
<span class="pl-c1">cd</span> meshroom
pip install -r requirements.txt</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone --recursive git://github.com/alicevision/meshroom
cd meshroom
pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动网状室</font></font></h2><a id="user-content-start-meshroom" class="anchor" aria-label="永久链接：启动 Meshroom" href="#start-meshroom"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您需要</font><font style="vertical-align: inherit;">在 PATH 中（以及 Linux/macOS 上的 LD_LIBRARY_PATH）安装</font></font><a href="https://github.com/alicevision/AliceVision"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AliceVision 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动用户界面</font></font></strong></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Windows</span>
<span class="pl-c1">set</span> PYTHONPATH=%CD% <span class="pl-k">&amp;&amp;</span> python meshroom/ui
<span class="pl-c"><span class="pl-c">#</span> Linux/macOS</span>
PYTHONPATH=<span class="pl-smi">$PWD</span> python meshroom/ui</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Windows
set PYTHONPATH=%CD% &amp;&amp; python meshroom/ui
# Linux/macOS
PYTHONPATH=$PWD python meshroom/ui" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Ubuntu 上，本机驱动程序和 mesa 驱动程序之间可能会发生冲突。在这种情况下，您需要通过将本机驱动程序添加到 LD_LIBRARY_PATH 来强制使用本机驱动程序：
您可能需要使用</font><font style="vertical-align: inherit;">正确的驱动程序版本</font></font><code>LD_LIBRARY_PATH=/usr/lib/nvidia-340 PYTHONPATH=$PWD python meshroom/ui</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
调整文件夹。</font></font><code>/usr/lib/nvidia-340</code><font style="vertical-align: inherit;"></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在命令行中启动 3D 重建</font></font></strong></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Windows: set PYTHONPATH=%CD% &amp;&amp;</span>
<span class="pl-c"><span class="pl-c">#</span> Linux/macOS: PYTHONPATH=$PWD</span>
python bin/meshroom_batch --input INPUT_IMAGES_FOLDER --output OUTPUT_FOLDER</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Windows: set PYTHONPATH=%CD% &amp;&amp;
# Linux/macOS: PYTHONPATH=$PWD
python bin/meshroom_batch --input INPUT_IMAGES_FOLDER --output OUTPUT_FOLDER" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在不构建 AliceVision 的情况下启动 Meshroom</font></font></h2><a id="user-content-start-meshroom-without-building-alicevision" class="anchor" aria-label="永久链接：在不构建 AliceVision 的情况下启动 Meshroom" href="#start-meshroom-without-building-alicevision"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在不构建 AliceVision 的情况下使用 Meshroom (ui)</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font><a href="https://github.com/alicevision/meshroom/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查相应的 Meshroom (ui) 版本/标签以避免版本不兼容</font></font></li>
<li><code>LD_LIBRARY_PATH=~/foo/Meshroom-2023.2.0/aliceVision/lib/ PATH=$PATH:~/foo/Meshroom-2023.2.0/aliceVision/bin/ PYTHONPATH=$PWD python3 meshroom/ui</code></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 IDE 中启动并调试 Meshroom</font></font></h2><a id="user-content-start-and-debug-meshroom-in-an-ide" class="anchor" aria-label="永久链接：在 IDE 中启动和调试 Meshroom" href="#start-and-debug-meshroom-in-an-ide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyCharm Community 是可以使用的免费 IDE。要使用该 IDE 启动和调试项目，请右键单击</font></font><code>Meshroom/ui/__main__.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&gt; </font></font><code>Debug</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，然后右键</font></font><code>Edit Configuration</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击</font></font><code>Environment variables</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果你想使用自己构建的 aliceVision 添加：</font></font><code>PATH=$PATH:/foo/build/Linux-x86_64/</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想使用 aliceVision 版本，请添加：（</font></font><code>LD_LIBRARY_PATH=/foo/Meshroom-2023.2.0/aliceVision/lib/;PATH=$PATH:/foo/Meshroom-2023.2.0/aliceVision/bin/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您位于与正确版本匹配的分支上）</font></font></li>
</ul>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/937836/127321375-3bf78e73-569d-414a-8649-de0307adf794.png"><img src="https://user-images.githubusercontent.com/937836/127321375-3bf78e73-569d-414a-8649-de0307adf794.png" alt="图像" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常问问题</font></font></h2><a id="user-content-faq" class="anchor" aria-label="永久链接：常见问题解答" href="#faq"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/alicevision/meshroom/wiki"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Meshroom wiki</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多信息。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接触</font></font></h2><a id="user-content-contact" class="anchor" aria-label="永久链接：联系方式" href="#contact"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用公共邮件列表提出问题或请求功能。它也是进行非正式讨论的好地方，例如分享成果、有趣的相关技术或出版物：</font></font></p>
<blockquote>
<p dir="auto"><a href="mailto:alicevision@googlegroups.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">alicevision@googlegroups.com </font></font></a>
<a href="http://groups.google.com/group/alicevision" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://groups.google.com/group/alicevision</font></font></a></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以私下联系核心团队：</font></font><a href="mailto:alicevision-team@googlegroups.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">alicevision-team@googlegroups.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</article></div>
