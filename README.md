# VapourX Open Forum

<div align="center">
  <img src="assets/vapourx-logo.png" alt="VapourX Logo" width="200" height="auto">
</div>

<!-- Language Toggle -->
<div align="center" style="margin: 20px 0;">
  <button onclick="showLanguage('en')" id="btn-en" style="padding: 8px 16px; margin: 0 5px; border: 2px solid #007bff; background: #007bff; color: white; border-radius: 5px; cursor: pointer;">English</button>
  <button onclick="showLanguage('zh')" id="btn-zh" style="padding: 8px 16px; margin: 0 5px; border: 2px solid #ddd; background: white; color: #333; border-radius: 5px; cursor: pointer;">中文</button>
</div>

<!-- English Content -->
<div id="content-en">
  <div align="center">
    <p><strong>Human-Machine Unity, Transforming Concrete into Abstract</strong></p>

    <p>
      <a href="https://github.com/ACondaway/vapourx/stargazers">
        <img src="https://img.shields.io/github/stars/ACondaway/vapourx?style=social" alt="GitHub stars">
      </a>
      <a href="https://github.com/ACondaway/vapourx/network/members">
        <img src="https://img.shields.io/github/forks/ACondaway/vapourx?style=social" alt="GitHub forks">
      </a>
      <a href="https://github.com/ACondaway/vapourx/issues">
        <img src="https://img.shields.io/github/issues/ACondaway/vapourx" alt="GitHub issues">
      </a>
      <a href="https://github.com/ACondaway/vapourx/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/ACondaway/vapourx" alt="License">
      </a>
    </p>
  </div>

  ## 📊 GitHub Star History

  <div align="center">
    <img src="https://api.star-history.com/svg?repos=ACondaway/vapourx&type=Date" alt="GitHub Star History Chart" width="600" height="auto" style="max-width: 100%; height: auto;">
  </div>

  ## 🚀 About VapourX

  VapourX is uniting a passionate community of embodied intelligence enthusiasts, professionals, and researchers to pioneer natural interaction among humans, digital humans, and robots — driving the seamless evolution of embodied intelligence from research to real-world impact across industry and innovation.

  ## 📚 Featured Content

  - **🎯 Exciting Papers**: Curated collection of influential research papers in robotics, computer vision, and machine learning
  - **📝 Daily Blog**: Daily embodied intelligence and AIGC learning records
  - **🔬 Research Highlights**: Latest developments in embodied intelligence research

  ## 🌐 Website

  Visit our website: [VapourX Open Forum](https://acondaway.github.io/vapourx/)

  ## 🤝 Contributing

  We welcome contributions! Please feel free to submit a Pull Request.

  ## 📄 License

  This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

  ---

  <div align="center">
    <p>Made with ❤️ by the VapourX Community</p>
  </div>
</div>

<!-- Chinese Content -->
<div id="content-zh" style="display: none;">
  <div align="center">
    <p><strong>人机合一，化具象为抽象</strong></p>

    <p>
      <a href="https://github.com/ACondaway/vapourx/stargazers">
        <img src="https://img.shields.io/github/stars/ACondaway/vapourx?style=social" alt="GitHub stars">
      </a>
      <a href="https://github.com/ACondaway/vapourx/network/members">
        <img src="https://img.shields.io/github/forks/ACondaway/vapourx?style=social" alt="GitHub forks">
      </a>
      <a href="https://github.com/ACondaway/vapourx/issues">
        <img src="https://img.shields.io/github/issues/ACondaway/vapourx" alt="GitHub issues">
      </a>
      <a href="https://github.com/ACondaway/vapourx/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/ACondaway/vapourx" alt="License">
      </a>
    </p>
  </div>

  ## 📊 GitHub Star 历史轨迹

  <div align="center">
    <img src="https://api.star-history.com/svg?repos=ACondaway/vapourx&type=Date" alt="GitHub Star History Chart" width="600" height="auto" style="max-width: 100%; height: auto;">
  </div>

  ## 🚀 关于 VapourX

  VapourX 正在团结一个充满激情的具身智能爱好者、专业人士和研究人员的社区，以开创人类、数字人和机器人之间的自然交互——推动具身智能从研究到跨行业和创新的现实世界影响的无缝演进。

  ## 📚 特色内容

  - **🎯 精彩论文**: 机器人学、计算机视觉和机器学习领域有影响力研究论文的精选集
  - **📝 每日博客**: 具身智能和 AIGC 学习记录的日常更新
  - **🔬 研究亮点**: 具身智能研究的最新发展

  ## 🌐 网站

  访问我们的网站: [VapourX 开放论坛](https://acondaway.github.io/vapourx/)

  ## 🤝 贡献

  我们欢迎贡献！请随时提交 Pull Request。

  ## 📄 许可证

  本项目采用 MIT 许可证 - 详情请参阅 [LICENSE](LICENSE) 文件。

  ---

  <div align="center">
    <p>由 VapourX 社区 ❤️ 制作</p>
  </div>
</div>

<script>
function showLanguage(lang) {
  // Hide all content
  document.getElementById('content-en').style.display = 'none';
  document.getElementById('content-zh').style.display = 'none';

  // Show selected content
  document.getElementById('content-' + lang).style.display = 'block';

  // Update button styles
  document.getElementById('btn-en').style.background = lang === 'en' ? '#007bff' : 'white';
  document.getElementById('btn-en').style.color = lang === 'en' ? 'white' : '#333';
  document.getElementById('btn-en').style.border = lang === 'en' ? '2px solid #007bff' : '2px solid #ddd';

  document.getElementById('btn-zh').style.background = lang === 'zh' ? '#007bff' : 'white';
  document.getElementById('btn-zh').style.color = lang === 'zh' ? 'white' : '#333';
  document.getElementById('btn-zh').style.border = lang === 'zh' ? '2px solid #007bff' : '2px solid #ddd';
}

// Set default language to English
showLanguage('en');
</script>


