# yesterday-todayAndTomorrow

原编号范围为 1–38，其中 9 号因编号遗漏而不存在，保留其余片段现有编号。排除用户指定不操作的 10 个编号，实际处理目标为 27 个。目前 27 个视频及其对应首帧已全部处理完成。

- `clips/`：用户原始片段，保留原始编号和视频内容，文件名统一去掉 V2、V3 等版本后缀，使用 Git LFS 保存。
- `firstPicture/`：每个已上传片段的第一帧 PNG，与视频使用同名文件（例如 `shot23.mp4` 对应 `shot23.png`）。
- `clips/manifest.csv`：当前已接收片段的尺寸、时长及 SHA-256 校验值。
- `codex分割版/`：此前自动切分的 164 个分镜与首帧，仅作历史归档，不用于后续工作。

已处理文件：shot2、shot3、shot4、shot5、shot6、shot7、shot8、shot10、shot11、shot12、shot13、shot15、shot16、shot18、shot20、shot21、shot23、shot24、shot26、shot27、shot29、shot31、shot32、shot33、shot34、shot36、shot38。

不操作编号：1、14、17、19、22、25、28、30、35、37。

处理状态：27/27 全部完成，无待处理片段；9 号不存在，不补号、不重排其他 clips。

后续工作使用上述 27 个用户片段及对应首帧，不以历史归档替代。压缩包不上传 GitHub。

shot23 使用用户最新上传的分卷版本更新，旧版本仅保留在 Git 历史中，不重复计入处理数量。
