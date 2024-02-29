<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://circleci.com/gh/MRPT/mvsim" rel="nofollow"><img src="https://camo.githubusercontent.com/7a01cc19252c87fe119d512995f3315ab69537d6f1e96995544c3bcdadbea56c/68747470733a2f2f636972636c6563692e636f6d2f67682f4d5250542f6d7673696d2e7376673f7374796c653d737667" alt="模拟仿真" data-canonical-src="https://circleci.com/gh/MRPT/mvsim.svg?style=svg" style="max-width: 100%;"></a> <a href="https://mvsimulator.readthedocs.io/en/latest/?badge=latest" rel="nofollow"><img src="https://camo.githubusercontent.com/98639a727e3e1499ff30c498329ffc80fc138bfcae599659d6b25ab96a4493fe/68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f6d7673696d756c61746f722f62616467652f3f76657273696f6e3d6c6174657374" alt="文件状态" data-canonical-src="https://readthedocs.org/projects/mvsimulator/badge/?version=latest" style="max-width: 100%;"></a>
<a href="https://github.com/MRPT/mvsim/actions/workflows/build-linux.yml"><img src="https://github.com/MRPT/mvsim/actions/workflows/build-linux.yml/badge.svg" alt="持续集成Linux" style="max-width: 100%;"></a>
<a href="https://github.com/MRPT/mvsim/actions/workflows/check-clang-format.yml"><img src="https://github.com/MRPT/mvsim/actions/workflows/check-clang-format.yml/badge.svg" alt="CI 检查 clang 格式" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多车辆模拟器 (MVSim)</font></font></h1><a id="user-content-multivehicle-simulator-mvsim" class="anchor-element" aria-label="永久链接：多车辆模拟器 (MVSim)" href="#multivehicle-simulator-mvsim"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 2D（“2.5D”）车辆和机器人的轻量级、逼真的动态模拟器。</font><font style="vertical-align: inherit;">它专为分析车辆动力学、车轮与地面接触力以及典型机器人传感器（例如 2D 和 3D 激光雷达）的精确模拟而定制。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该软件包包括 C++ 库、独立应用程序以及 ROS 1 和 ROS 2 节点。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可证：3-clause BSD 许可证 版权所有 (C) 2014-2023 Jose Luis Blanco </font></font><a href="mailto:jlblanco@ual.es"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">jlblanco@ual.es</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（阿尔梅里亚大学）和合作者</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://www.sciencedirect.com/science/article/pii/S2352711023001395" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MVSim SoftwareX 论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（或</font></font><a href="https://arxiv.org/abs/2302.11033" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArXiV 预印本</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），了解项目架构的简要介绍。</font><font style="vertical-align: inherit;">如果您想在您的工作中引用 MVSim，请使用：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@article{blanco2023mvsim,
  title = {MultiVehicle Simulator (MVSim): Lightweight dynamics simulator for multiagents and mobile robotics research},
  journal = {SoftwareX},
  volume = {23},
  pages = {101443},
  year = {2023},
  issn = {2352-7110},
  doi = {https://doi.org/10.1016/j.softx.2023.101443},
  url = {https://www.sciencedirect.com/science/article/pii/S2352711023001395},
  author = {José-Luis Blanco-Claraco and Borys Tymchenko and Francisco José Mañas-Alvarez and Fernando Cañadas-Aránega and Ángel López-Gázquez and José Carlos Moreno}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{blanco2023mvsim,
  title = {MultiVehicle Simulator (MVSim): Lightweight dynamics simulator for multiagents and mobile robotics research},
  journal = {SoftwareX},
  volume = {23},
  pages = {101443},
  year = {2023},
  issn = {2352-7110},
  doi = {https://doi.org/10.1016/j.softx.2023.101443},
  url = {https://www.sciencedirect.com/science/article/pii/S2352711023001395},
  author = {José-Luis Blanco-Claraco and Borys Tymchenko and Francisco José Mañas-Alvarez and Fernando Cañadas-Aránega and Ángel López-Gázquez and José Carlos Moreno}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-installation" class="anchor-element" aria-label="永久链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关所有详细信息和选项，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://mvsimulator.readthedocs.io/en/latest/install.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装文档。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您已经有 ROS 1 或 ROS 2，最简单的安装方法是：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>sudo apt install ros-$ROS_DISTRO-mvsim
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo apt install ros-$ROS_DISTRO-mvsim" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后跳转到</font></font><a href="https://mvsimulator.readthedocs.io/en/latest/first-steps.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后续步骤</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，了解如何启动一些演示世界。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示视频</font></font></h2><a id="user-content-demo-videos" class="anchor-element" aria-label="永久链接：演示视频" href="#demo-videos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/MRPT/mvsim/blob/develop/docs/imgs/mvsim-ros2-demo.gif" data-target="animated-image.originalLink"><img src="/MRPT/mvsim/raw/develop/docs/imgs/mvsim-ros2-demo.gif" alt="截图演示" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
     </p>
<p dir="auto"><a href="https://www.youtube.com/watch?v=xMUMjEG8xlk" rel="nofollow"><img src="https://camo.githubusercontent.com/dae3e593408027f223aee7c2ccd16358c960dd94edc1e446287a5a677d6a0e52/68747470733a2f2f696d672e796f75747562652e636f6d2f76692f784d554d6a454738786c6b2f302e6a7067" alt="MvSim简介" data-canonical-src="https://img.youtube.com/vi/xMUMjEG8xlk/0.jpg" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建矩阵状态</font></font></h2><a id="user-content-build-matrix-status" class="anchor-element" aria-label="永久链接：构建矩阵状态" href="#build-matrix-status"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发行版</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建开发</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建版本</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稳定版</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS 1 思维 (u20.04)</font></font></td>
<td><a href="https://build.ros.org/job/Ndev__mvsim__ubuntu_focal_amd64/" rel="nofollow"><img src="https://camo.githubusercontent.com/3900aee23fb0e993ab236d0dd888a7fa860e03469a7fda7d872ec40571884e69/68747470733a2f2f6275696c642e726f732e6f72672f6a6f622f4e6465765f5f6d7673696d5f5f7562756e74755f666f63616c5f616d6436342f62616467652f69636f6e" alt="构建状态" data-canonical-src="https://build.ros.org/job/Ndev__mvsim__ubuntu_focal_amd64/badge/icon" style="max-width: 100%;"></a></td>
<td><a href="https://build.ros.org/job/Nbin_uF64__mvsim__ubuntu_focal_amd64__binary/" rel="nofollow"><img src="https://camo.githubusercontent.com/2fefdde53dae4566655a09a17872137d4fbf9261b076fb229186ee642c135f72/68747470733a2f2f6275696c642e726f732e6f72672f6a6f622f4e62696e5f754636345f5f6d7673696d5f5f7562756e74755f666f63616c5f616d6436345f5f62696e6172792f62616467652f69636f6e" alt="构建状态" data-canonical-src="https://build.ros.org/job/Nbin_uF64__mvsim__ubuntu_focal_amd64__binary/badge/icon" style="max-width: 100%;"></a></td>
<td><a href="https://index.ros.org/search/?term=mvsim" rel="nofollow"><img src="https://camo.githubusercontent.com/7cca26cdcedddc1b64e491305225e86c0b22c43b5c48f5320c10ff677cc8803c/68747470733a2f2f696d672e736869656c64732e696f2f726f732f762f6e6f657469632f6d7673696d" alt="版本" data-canonical-src="https://img.shields.io/ros/v/noetic/mvsim" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS 2 谦虚 (u22.04)</font></font></td>
<td><a href="https://build.ros2.org/job/Hdev__mvsim__ubuntu_jammy_amd64/" rel="nofollow"><img src="https://camo.githubusercontent.com/58831219ae08a6e676fa35ecd0eba59f4a836b844767f8abbb595412e84379f2/68747470733a2f2f6275696c642e726f73322e6f72672f6a6f622f486465765f5f6d7673696d5f5f7562756e74755f6a616d6d795f616d6436342f62616467652f69636f6e" alt="构建状态" data-canonical-src="https://build.ros2.org/job/Hdev__mvsim__ubuntu_jammy_amd64/badge/icon" style="max-width: 100%;"></a></td>
<td><a href="https://build.ros2.org/job/Hbin_uJ64__mvsim__ubuntu_jammy_amd64__binary/" rel="nofollow"><img src="https://camo.githubusercontent.com/734a2eece9571dc11acd18f00a809ee58690fcb42c12297886fbdbed943441a1/68747470733a2f2f6275696c642e726f73322e6f72672f6a6f622f4862696e5f754a36345f5f6d7673696d5f5f7562756e74755f6a616d6d795f616d6436345f5f62696e6172792f62616467652f69636f6e" alt="构建状态" data-canonical-src="https://build.ros2.org/job/Hbin_uJ64__mvsim__ubuntu_jammy_amd64__binary/badge/icon" style="max-width: 100%;"></a></td>
<td><a href="https://index.ros.org/search/?term=mvsim" rel="nofollow"><img src="https://camo.githubusercontent.com/122e1cb5aceeb78a6adceef9fa296272341de845b27cbaf6d4ab761e865922bd/68747470733a2f2f696d672e736869656c64732e696f2f726f732f762f68756d626c652f6d7673696d" alt="版本" data-canonical-src="https://img.shields.io/ros/v/humble/mvsim" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS 2 铁 (u22.04)</font></font></td>
<td><a href="https://build.ros2.org/job/Idev__mvsim__ubuntu_jammy_amd64/" rel="nofollow"><img src="https://camo.githubusercontent.com/7d25585b31cc3c67c81e704e13b7494ef4489a709cc12ba1e88e54c8fc68d3d2/68747470733a2f2f6275696c642e726f73322e6f72672f6a6f622f496465765f5f6d7673696d5f5f7562756e74755f6a616d6d795f616d6436342f62616467652f69636f6e" alt="构建状态" data-canonical-src="https://build.ros2.org/job/Idev__mvsim__ubuntu_jammy_amd64/badge/icon" style="max-width: 100%;"></a></td>
<td><a href="https://build.ros2.org/job/Ibin_uJ64__mvsim__ubuntu_jammy_amd64__binary/" rel="nofollow"><img src="https://camo.githubusercontent.com/b90de749e9787f6a2bfd256ce7582eee774ab81dc19f3426815931ffecd6a9ac/68747470733a2f2f6275696c642e726f73322e6f72672f6a6f622f4962696e5f754a36345f5f6d7673696d5f5f7562756e74755f6a616d6d795f616d6436345f5f62696e6172792f62616467652f69636f6e" alt="构建状态" data-canonical-src="https://build.ros2.org/job/Ibin_uJ64__mvsim__ubuntu_jammy_amd64__binary/badge/icon" style="max-width: 100%;"></a></td>
<td><a href="https://index.ros.org/search/?term=mvsim" rel="nofollow"><img src="https://camo.githubusercontent.com/2620a3280531297d3edd84c8cda2f6e04e7d5ad58ad4c931c258b1ea0f691258/68747470733a2f2f696d672e736869656c64732e696f2f726f732f762f69726f6e2f6d7673696d" alt="版本" data-canonical-src="https://img.shields.io/ros/v/iron/mvsim" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS 2 滚动 (u22.04)</font></font></td>
<td><a href="https://build.ros2.org/job/Rdev__mvsim__ubuntu_jammy_amd64/" rel="nofollow"><img src="https://camo.githubusercontent.com/04aa48ff3e19a6f85c3ee626703e915860d2e5c1e00dd3c90a262b3b36e79f62/68747470733a2f2f6275696c642e726f73322e6f72672f6a6f622f526465765f5f6d7673696d5f5f7562756e74755f6a616d6d795f616d6436342f62616467652f69636f6e" alt="构建状态" data-canonical-src="https://build.ros2.org/job/Rdev__mvsim__ubuntu_jammy_amd64/badge/icon" style="max-width: 100%;"></a></td>
<td><a href="https://build.ros2.org/job/Rbin_uJ64__mvsim__ubuntu_jammy_amd64__binary/" rel="nofollow"><img src="https://camo.githubusercontent.com/912014ba101c5bbe5227424cfcb67f09f5d9d1bb84c3d9f4cce9432ef7002062/68747470733a2f2f6275696c642e726f73322e6f72672f6a6f622f5262696e5f754a36345f5f6d7673696d5f5f7562756e74755f6a616d6d795f616d6436345f5f62696e6172792f62616467652f69636f6e" alt="构建状态" data-canonical-src="https://build.ros2.org/job/Rbin_uJ64__mvsim__ubuntu_jammy_amd64__binary/badge/icon" style="max-width: 100%;"></a></td>
<td><a href="https://index.ros.org/search/?term=mvsim" rel="nofollow"><img src="https://camo.githubusercontent.com/fbcd6a3f92da508d6a7b86413a8f4abc7d3d16d9b18f8c677d8826a441b124da/68747470733a2f2f696d672e736869656c64732e696f2f726f732f762f726f6c6c696e672f6d7673696d" alt="版本" data-canonical-src="https://img.shields.io/ros/v/rolling/mvsim" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">停产发行版</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稳定版</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS 1 旋律 (u18.04)</font></font></td>
<td><a href="https://index.ros.org/search/?term=mvsim" rel="nofollow"><img src="https://camo.githubusercontent.com/4454f8865c522ef1c77c2762940ad44152a5eee93025badb42f9af2be0a08e8a/68747470733a2f2f696d672e736869656c64732e696f2f726f732f762f6d656c6f6469632f6d7673696d" alt="版本" data-canonical-src="https://img.shields.io/ros/v/melodic/mvsim" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS 2 狐狸 (u20.04)</font></font></td>
<td><a href="https://index.ros.org/search/?term=mvsim" rel="nofollow"><img src="https://camo.githubusercontent.com/539e811b901c6f67b7ac14d03cc9efaf1906f034164be600fc75d950e331c747/68747470733a2f2f696d672e736869656c64732e696f2f726f732f762f666f78792f6d7673696d" alt="版本" data-canonical-src="https://img.shields.io/ros/v/foxy/mvsim" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-docs" class="anchor-element" aria-label="永久链接：文档" href="#docs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://mvsimulator.readthedocs.io/en/latest/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要文档站点</font></font></a></li>
<li><a href="https://wiki.ros.org/mvsim" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://wiki.ros.org/mvsim</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您克隆此存储库，请记住也检查 git 子模块：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://github.com/MRPT/mvsim.git --recursive
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/MRPT/mvsim.git --recursive" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动演示</font></font></h2><a id="user-content-launch-demos" class="anchor-element" aria-label="永久链接：启动演示" href="#launch-demos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://mvsimulator.readthedocs.io/en/latest/first-steps.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看有关第一步的更多信息</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">独立：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>mvsim launch mvsim_tutorial/demo_warehouse.world.xml
mvsim launch mvsim_tutorial/demo_2robots.world.xml
mvsim launch mvsim_tutorial/test_mesh.world.xml
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mvsim launch mvsim_tutorial/demo_warehouse.world.xml
mvsim launch mvsim_tutorial/demo_2robots.world.xml
mvsim launch mvsim_tutorial/test_mesh.world.xml" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">活性氧1：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>roslaunch mvsim demo_depth_camera.launch
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="roslaunch mvsim demo_depth_camera.launch" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">活性氧2：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>ros2 launch mvsim demo_warehouse.launch.py
ros2 launch mvsim demo_depth_camera.launch.py
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ros2 launch mvsim demo_warehouse.launch.py
ros2 launch mvsim demo_depth_camera.launch.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要特点</font></font></h2><a id="user-content-main-features" class="anchor-element" aria-label="永久链接：主要特点" href="#main-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内存、CPU 和库要求轻量级。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过</font></font><code>.xml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“世界”文件完全可配置。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Headless 模式，适用于 dockerized 环境。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">世界地图：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占用网格图：作为图像或 MRPT 二进制地图输入（来自 icp-slam、rbpf-slam 等）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高程网格。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">车型：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">差速驱动（2 轮和 4 轮驱动）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿克曼转向（运动和动态转向，不同的机械驱动模型）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿克曼转向系统配备全级机械差速器。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">传感器：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2D 和 3D 激光雷达：机器人可以看到彼此、自己的身体等。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RGB相机</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">深度相机</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">车辆接口：自定义 Python 接口或 ROS。</font><font style="vertical-align: inherit;">选择：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对力和电机扭矩的原始访问。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扭转命令（使用内部控制器）。</font></font></li>
</ul>
</li>
</ul>
</article></div>
