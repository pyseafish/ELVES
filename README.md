# ELVES - Amateur Radio QSO Logger / 业余无线电通联日志系统

## Basic Introduction / 基本介绍
ELVES is a modern, browser-based amateur radio QSO logging application developed by **BG5DHV**, with partial development assistance from **Deepseek**. It provides a complete local-first solution for radio enthusiasts to record, manage, and export communication logs without relying on external servers.

ELVES 是一个现代化的基于浏览器的业余无线电通联日志应用，由 **BG5DHV** 开发，部分开发由 **Deepseek** 辅助完成。它为无线电爱好者提供了一个完整的本地优先解决方案，用于记录、管理和导出通联日志，无需依赖外部服务器。

## Key Features / 特色功能
- **🏠 Local-First Architecture**: All data stored locally in browser, ensuring privacy and offline capability
- **📱 Mobile-Optimized UI**: Responsive design tailored for mobile devices with native app-like experience
- **🌐 Multi-Language Support**: Simplified Chinese, Traditional Chinese, English, and Japanese interfaces
- **🎯 Contest-Specific Logging**: Dedicated fields for major contests (CQ WPX, CQWW, WAPC) with automatic format adaptation
- **📤 Flexible Export**: Support for ADI and Cabrillo formats with contest-specific templates
- **🎨 Theme System**: Light/Dark mode with professional color schemes
- **🔍 Advanced Filtering**: Comprehensive filtering by date, callsign, grid, and contest type

- **🏠 本地优先架构**: 所有数据本地存储在浏览器中，确保隐私和离线能力
- **📱 移动优化界面**: 响应式设计，专为移动设备优化，提供类似原生应用的体验
- **🌐 多语言支持**: 简体中文、繁体中文、英文和日文界面
- **🎯 比赛专用日志**: 为主要比赛（CQ WPX、CQWW、WAPC）提供专用字段，自动格式适配
- **📤 灵活导出**: 支持 ADI 和 Cabrillo 格式，包含比赛专用模板
- **🎨 主题系统**: 浅色/深色模式，专业配色方案
- **🔍 高级筛选**: 按日期、呼号、网格和比赛类型全面筛选

## Technical Stack / 技术栈
- **Frontend**: Pure HTML5 + CSS3 + Vanilla JavaScript
- **Storage**: Browser localStorage with IndexedDB-ready architecture
- **Styling**: CSS Grid/Flexbox with CSS Custom Properties for theming
- **Fonts**: Inter font family for modern typography
- **Export**: Blob API for file generation and download

- **前端**: 纯 HTML5 + CSS3 + 原生 JavaScript
- **存储**: 浏览器 localStorage，具备 IndexedDB 就绪架构
- **样式**: CSS Grid/Flexbox，使用 CSS 自定义属性实现主题
- **字体**: Inter 字体家族，现代排版
- **导出**: Blob API 用于文件生成和下载

## Architecture Highlights / 架构亮点
- Zero external dependencies - runs entirely in browser sandbox
- Modular JavaScript with centralized state management
- Custom UI components replacing native browser controls
- Efficient data serialization/deserialization for import/export operations
- Graceful degradation for older browsers

- 零外部依赖 - 完全在浏览器沙箱中运行
- 模块化 JavaScript 与集中式状态管理
- 自定义 UI 组件替代原生浏览器控件
- 高效的数据序列化/反序列化用于导入/导出操作
- 对旧版浏览器的优雅降级

**License**: MIT Open Source  
**开源协议**: MIT 许可证
