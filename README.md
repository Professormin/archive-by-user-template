# 按用户模板归档与交接

下载 Release ZIP 并解压。将整个 archive-by-user-template 文件夹放入支持 SKILL.md 的客户端技能目录。Codex 可将它放入项目的 .agents/skills/ 下，再在该项目中调用。

示例调用：“用按用户模板归档与交接，把我已经验证的字幕设置整理成知识卡。用内置模板，输出到当前项目。”

入口是 SKILL.md。templates 是知识卡和交接单模板，examples 是虚构素材的输出示例。需要一个支持读取本地 Markdown 的 Skill 客户端，无需额外库或账号凭据。输出为 Markdown。
