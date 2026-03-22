# Tampermonkey Scripts

> Personal userscripts for improving daily web workflows. GreasyFork is the primary install channel, GitHub is the source repository.

## Script List

| Script | Site | Core Benefit | Install | Status |
|--------|------|--------------|---------|--------|
| [微信读书沉浸式进度显示](weread-progress.js) | [微信读书](https://weread.qq.com) | 在阅读页右下角显示更平滑、更连续的实时阅读进度 | [GreasyFork](https://greasyfork.org/zh-CN/scripts/558200-%E5%BE%AE%E4%BF%A1%E8%AF%BB%E4%B9%A6%E6%B2%89%E6%B5%B8%E5%BC%8F%E8%BF%9B%E5%BA%A6%E6%98%BE%E7%A4%BA) | Published |
| [微信读书单页阅读模式](weread-single.js) | [微信读书](https://weread.qq.com) | 强制关闭双栏布局，恢复居中的单页阅读体验 | [GreasyFork](https://greasyfork.org/zh-CN/scripts/570563-%E5%BE%AE%E4%BF%A1%E8%AF%BB%E4%B9%A6%E5%8D%95%E9%A1%B5%E9%98%85%E8%AF%BB%E6%A8%A1%E5%BC%8F) | Published |
| [AutoDL 部署列表增强](autodl-enhancer.js) | [AutoDL](https://www.autodl.com) | 自动扩展分页、隐藏测试实例，并按实时费用排序 | [GreasyFork](https://greasyfork.org/zh-CN/scripts/570559-autodl-%E9%83%A8%E7%BD%B2%E5%88%97%E8%A1%A8%E5%A2%9E%E5%BC%BA) | Published |
| [Markdown 标题快捷键统一](md-hotkeys.js) | 幕布 / 语雀 / 飞书 | 为常用文档工具统一 `Cmd/Ctrl + 1~6` 标题快捷键 | [GreasyFork](https://greasyfork.org/zh-CN/scripts/570560-markdown-%E6%A0%87%E9%A2%98%E5%BF%AB%E6%8D%B7%E9%94%AE%E7%BB%9F%E4%B8%80) | Published |
| [幕布侧边栏精简与一键展开](mubu-enhancer.js) | [幕布](https://mubu.com) | 精简侧边栏入口，并新增一键展开一级节点按钮 | [GreasyFork](https://greasyfork.org/zh-CN/scripts/570561-%E5%B9%95%E5%B8%83%E4%BE%A7%E8%BE%B9%E6%A0%8F%E7%B2%BE%E7%AE%80%E4%B8%8E%E4%B8%80%E9%94%AE%E5%B1%95%E5%BC%80) | Published |
| [语雀编辑增强](yuque-enhancer.js) | [语雀](https://yuque.com) | 移除冗余菜单、自动进入编辑模式，并让标题锚点常驻可见 | [GreasyFork](https://greasyfork.org/zh-CN/scripts/570564-%E8%AF%AD%E9%9B%80%E7%BC%96%E8%BE%91%E5%A2%9E%E5%BC%BA) | Published |
| [时光序菜单精简与事项重命名](shiguangxu.js) | [时光序](https://shiguangxu.com) | 隐藏低频菜单，精简事项筛选，并优化“清单”命名 | [GreasyFork](https://greasyfork.org/zh-CN/scripts/570562-%E6%97%B6%E5%85%89%E5%BA%8F%E8%8F%9C%E5%8D%95%E7%B2%BE%E7%AE%80%E4%B8%8E%E4%BA%8B%E9%A1%B9%E9%87%8D%E5%91%BD%E5%90%8D) | Published |

## Notes

- [微信读书沉浸式进度显示](weread-progress.js)：适用于微信读书阅读页，通过 DOM 进度与滚动距离混合估算，显示更顺滑。
- [微信读书单页阅读模式](weread-single.js)：适用于宽屏阅读场景，核心目标是去掉双栏并保持内容居中。
- [AutoDL 部署列表增强](autodl-enhancer.js)：适用于部署列表页，优先解决翻页数量太小、测试实例干扰和费用比较不直观的问题。
- [Markdown 标题快捷键统一](md-hotkeys.js)：适用于频繁在多个编辑器切换的用户，减少不同站点快捷键不一致带来的成本。
- [幕布侧边栏精简与一键展开](mubu-enhancer.js)：适用于资料较多的幕布用户，减少侧边栏噪音并提升大纲展开效率。
- [语雀编辑增强](yuque-enhancer.js)：适用于以编辑为主的语雀使用方式，减少进入编辑态和查看标题锚点的额外操作。
- [时光序菜单精简与事项重命名](shiguangxu.js)：适用于偏 GTD/清单流的用户，减少菜单噪音并让事项分类命名更直观。

## Install

1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. Use the GreasyFork links in the table above as the primary install path.
3. This repository keeps the source files and issue tracker: [unix2dos/user_scripts](https://github.com/unix2dos/user_scripts).

## Support

- Source: [unix2dos/user_scripts](https://github.com/unix2dos/user_scripts)
- Issues: [GitHub Issues](https://github.com/unix2dos/user_scripts/issues)

## License

MIT
